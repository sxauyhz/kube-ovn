# CHANGELOG

## v0.3.0 -- 2019/04/19
### Features
* Namespaced Gateway for external connectivity
* Daemon ovn-nbctl to improve performance
### Fix
* Daemon init node gw before running controller
* Activate node switch by ping
* Fix ovn-nbctl daemon output format bugs
* ACL allow error

## v0.2.0 -- 2019/04/15
### Features
* Distributed Gateway for external connectivity
* Dynamic QoS for pod ingress/egress bandwidth
* Subnet isolation
### Bug Fixes
* Delete empty lb to improve performance
* Delete lb at node switch
* Delete ovn embedded dns
* Fix ovn restart failed issue


## v0.1.0 -- 2019/03/12
### Features
* IP/Mac automatic allocation
* IP/Mac static allocation
* Namespace bind subnet
* Namespaces share subnet
* Connectivity between node and pod 
### Issues
* Pod can not access external network
* No HA for control plan
