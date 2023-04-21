FROM php:8.1.18-fpm-alpine3.17
RUN docker-php-ext-install pdo pdo_mysql
RUN apk add nginx
EXPOSE 80
CMD [ "sh","-c","nginx && php-fpm" ]
