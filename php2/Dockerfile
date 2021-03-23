FROM php:7.2-apache

COPY . /var/www/html

EXPOSE 80

RUN usermod -u 1000 www-data; \
    chown -R www-data:www-data /var/www/html