# Existing-Wordpress-Docker-Image-With-Phpmyadmin

1. Place the sql dump under /etc/docker-entrypoint-initdb.d
2. Create ./blog folder and copy all wordpress files underneath.
3. Make sure to update the database config in wp-config.php
4. run docker-compose up --build
5. Access your site at localhost:8080 and phpmyadmin at localhost:8181
