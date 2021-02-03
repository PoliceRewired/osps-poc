# OSPS - the open source policing service

This is a community project, which will grow over time as we add more components.

The OSPS is a sample infrastructure for a policing service, built with open source components.

* Directory service: [OpenLDAP](https://www.openldap.org/)
* MDM service: [Headwind MDM](https://h-mdm.com/) (community edition)

## Prerequisites

This repository uses `docker-compose` to containerise an initialise a number of products and tools.

You will need to install:

* [docker](https://www.docker.com/) ([desktop edition](https://www.docker.com/products/docker-desktop) works fine)

## Running the services

```bash
./start.sh
```

Allow 1-2 mins for the services to initialise.

## Exploring the services

### Directory (OpenLDAP)

* Visit: http://localhost:8001
* Credentials: cn=admin,dc=osps,dc=local / test1234

### MDM (Headwind MDM, community edition)

* Visit: http://localhost:8002/hmdm
* Credentials: admin / admin
