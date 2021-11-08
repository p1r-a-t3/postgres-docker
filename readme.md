# Postgresql & PgAdmin powered by compose

Took help from: https://github.com/khezen/compose-postgres
Made for self-use.

## Quick Start

* Clone or download this repository
* Go inside of directory,  `cd compose-postgres`
* Run this command `docker-compose up -d`

## Access to postgres

* `localhost:5432`
* **Username:** postgres (as a default)
* **Password:** changeme (as a default)

## Access to PgAdmin

* **URL:** `http://localhost:12345`
* **Username:** pgadmin4@pgadmin.org (as a default)
* **Password:** admin (as a default)

## Add a new server in PgAdmin

* **Host name/address** `postgres`
* **Port** `5432`
* **Username** by default: `postgres`
* **Password** by default `changeme`