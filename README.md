# Nginx proxy

## Description

This service will:
* manage HTTPS endpoints
* force HTTPS connections
* expose metrology informations about trafic


## Deployment and usage

* [Ansible role](https://github.com/infOpen-Deployments/ansible-role-compose-nginx-proxy.git)

Expected networks:
* `services` : used for services to link with Nginx reverse proxy service
