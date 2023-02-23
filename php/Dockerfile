ARG PHP_VERSION

FROM php:${PHP_VERSION}-apache
RUN apt update && apt upgrade -y
RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli
