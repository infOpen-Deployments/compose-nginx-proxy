# Nginx proxy

## Description

This service will:
* manage HTTPS endpoints
* force HTTPS connections
* expose metrology informations about trafic


## Deployment and usage

* [Ansible role](https://gitlab.com/infopen/infrastructure/ansible-roles/ansible-role-nginx-proxy)

Expected networks:
* `services` : used for services to link with Nginx reverse proxy service
