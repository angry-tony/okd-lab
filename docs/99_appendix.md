# Appendix

## URL's and superuser logins

| Service  	| URL  	| Admin  	| Password  	|
|---	|---	|---	|---	|
| Cockpit*  	| http://localhost:9090  	| lab  	| unix account  	|
| Mirrors  	| http://mirror.okd.example.com  	|   	|   	|
| Load Balancer statistics  	| http://lb.okd.example.com:9000  	|   	|   	|
| GitLab*  	| http://gitlab.okd.example.com:8888  	| admin  	| passpass  	|
| Quay  	| http://quay.okd.example.com:5000  	| admin  	| admin  	|
| Artifactory*  	| http://artifactory.okd.example.com:7777  	| admin  	| password  	|
| Keycloak*  	| http://keycloak.okd.example.com:4444  	| admin  	| passpass  	|
| Portainer*  	| http://portainer.okd.example.com:9999  	| admin  	| passpass  	|

*Please Note: Admin/Root Accounts of these services are mostly not maintained with LDAP.

## Users in OpenLDAP user registry

| Username  	| Password  	| Email  	|
|---	|---	|---	|
| admin  	| admin  	| admin@example.com  	|
| administrator  	| administrator  	| administrator@example.com  	|
| kubeadmin  	| kubeadmin  	| kubeadmin@example.com  	|
| lab  	| lab  	| lab@example.com  	|
| developer  	| developer  	| developer@example.com  	|

## Software Versions

| Software  	| Version  	|
|---	|---	|
| CentOS  	| 7.8.2003  	|
| KVM/QEMU  	| 2.12.0  	|   	|
| Terraform  	| 0.12.28  	|
| Terraform KVM Plugin  	| v0.6.2  	|
| Packer  	| 1.6.0  	|
| Ansible  	| 2.9.10  	|
| Portainer  	| 1.24.0  	|
| Project Quay  	| qui-gon  	|
| Keycloak  	| 10.0.2  	|
| Artifacory  	| 7.6.1  	|
| GitLab  	| 13.0.7-ce.0  	|

## Network

Inspect the DNS [example.com zone file](https://github.com/disposab1e/okd-lab/blob/master/ansible/bastion/roles/bind/templates/db.example.com.j2) to get an overview.
