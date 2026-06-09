FROM postgres:15

ENV POSTGRES_DB=employeedb
ENV POSTGRES_USER=postgres
ENV POSTGRES_PASSWORD=2006

COPY init.sql /docker-entrypoint-initdb.d/init.sql

