FROM mysql:latest

ENV MYSQL_ROOT_PASSWORD=root
ENV MYSQL_DATABASE=gowtdb
ENV MYSQL_USER=gowt
ENV MYSQL_PASSWORD=super_secret_password

COPY ./script/script.sql /docker-entrypoint-initdb.d/script.sql

EXPOSE 3306
