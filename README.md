# Docker Compose for Postgres + PGAdmin

Turnkey deployment for postgres & pgadmin, with health checks and persistence using Docker Compose v2

## Prereqs

* docker >= 17
* docker-compose (Optional, compose v2 is now [part of docker](https://docs.docker.com/compose/compose-v2/))

## Quick Start

* Clone this repository `git clone https://github.com/amithkk/docker-compose-postgres.git`
* Go to the directory `cd docker-compose-postgres`
* Run this command `docker compose up -d` OR use `docker-compose up -d`

## Configuration Options and Default Credentials

This Compose file contains the following environment variables:

* `POSTGRES_USER` the default value is **postgres**
* `POSTGRES_PASSWORD` the default value is **postgres**
* `PGADMIN_PORT` the default value is **5050**
* `PGADMIN_DEFAULT_EMAIL` the default value is **pgadmin4@pgadmin.org**
* `PGADMIN_DEFAULT_PASSWORD` the default value is **pgadmin**
