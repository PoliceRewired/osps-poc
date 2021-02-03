# OSPS - the open source policing service

This is a community project, which will grow over time as we add more components.

The OSPS is a sample infrastructure for a policing service, built with open source components.

* Directory service: [OpenLDAP](https://www.openldap.org/)
* MDM service: [Headwind MDM](https://h-mdm.com/) (community edition)

## Why?

Policing could benefit from the advantages of open source software, open standards, and open data.

Benefits of open source software to public safety:

* Freely available software, interoperable with standards used across industry.
* Software can be more easily assessed, vulnerabilities more quickly identified.
* Policing becomes easier to trust as processes and procedures are made visible.
* Civic tech communities may contribute to projects to benefit public safety.
* Open APIs and technology stacks allow policing to respond to new pressures and demands by building new tools and applications.
* Fewer licenses to pay, maintenance can be done by technical staff.
* Open standards create a fair and open ecosystem for new applications.

## Prerequisites

This repository uses `docker-compose` to containerise and initialise a number of products and tools.

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
