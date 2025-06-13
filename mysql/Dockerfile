FROM mysql:8.0

#Environment variables
ENV MYSQL_ROOT_PASSWORD = App@2025

COPY schema/*.sql /docker-entrypoint-initdb.d/
