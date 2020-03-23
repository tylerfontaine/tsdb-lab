# Timescale Automation

For Timescale/grafana/pgadmin testing and learning automation

Requirements:
- Docker
- docker-compose

Just run `docker-compose up` from this directory, and you'll have a running Postgres 11 using the timescale:latest-pg11 image.
It will also run a copy of grafana, and pgadmin4.

Postgres is available on `localhost:5432`  
Grafana is available on `localhost:3000`  
pgadmin4 is available on `localhost:80`  

## Credentials

Postgres default username and password: `postgres` `password`  
Grafana default username and password: `admin` `admin`  
pgadmin4 default email and password: `email@example.com` `password`  

This is obviously not secure, and is for lab use only.
