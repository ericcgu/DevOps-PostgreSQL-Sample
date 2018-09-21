FROM postgres:10.4-alpine

# run create.sql on init
ADD ./db /docker-entrypoint-initdb.d
