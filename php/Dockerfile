FROM php:7.2.7-fpm-alpine3.7
RUN apk update; \
    apk upgrade;

RUN set -ex \
  && apk --no-cache add \
    postgresql-dev

RUN docker-php-ext-install pdo pdo_pgsql
