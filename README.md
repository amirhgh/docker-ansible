# Ansible Docker

A simple Ansible Role to install [Docker](https://www.docker.com) and docker-compose on any Linux

## How to work 

```
ansible-playbook -i inventory.ini -b play.yml
```
# Support variables
to force install docker or update docker version use
```
force_to_install=true
```
[@dwsclass](https://github.com/dwsclass/) dws-ops-003-ansible