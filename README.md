# Existing Wordpress Docker Image With Phpmyadmin

Steps to dockerize existing wordpress application using docker compose.

1. Create folder and place the sql dump under ./etc/docker-entrypoint-initdb.d/DUMP.sql
2. Create ./blog folder and copy all wordpress files underneath.
3. Make sure to update the database config in wp-config.php
4. run `docker-compose up --build`
5. Access your site at localhost:8080 and phpmyadmin at localhost:8181
