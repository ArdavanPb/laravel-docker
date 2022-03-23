FROM php:8.1.4-fpm-alpine
RUN docker-php-ext-install pdo pdo_mysql
WORKDIR /var/www/html
#RUN mkdir /var/www/html/storage/logs/laravel.log
#RUN chown -R www-data:www-data *