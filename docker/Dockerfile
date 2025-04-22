# Utiliza la ultima imagen oficial de MYSQL compatible con ARM64
FROM mysql/mysql-server:latest

# Define variables de entorno
ENV MYSQL_ROOT_PASSWORD=password
ENV MYSQL_DATABASE=mydatabase
ENV MYSQL_USER=myuser
ENV MYSQL_PASSWORD=password

# crea la base de datos en Docker
COPY ./create.sql /docker-entrypoint-initdb-d/