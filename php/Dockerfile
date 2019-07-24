FROM php:7.2-fpm
RUN apt update
RUN apt install less \
  && pecl install xdebug
COPY ./conf/php.ini $PHP_INI_DIR

