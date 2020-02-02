## Simple testbed for Postgrest

https://postgrest.org/
https://github.com/PostgREST/postgrest

Nice for unit tests

## Install

- Install postgrest binary in this direc https://github.com/PostgREST/postgrest/releases/
- make sure your logged in as the postgresql super user (not the same as root)
- read the makefile and edit your postgresql conf files
- run `make create-db` 
- run `make start-server` 
- run `curl localhost:3000/v_testing?limit=5`
