FROM serversideup/php:8.3-fpm-alpine-v3.3.0 as base
USER root

RUN install-php-extensions http raphf  intl exif bcmath

USER www-data
FROM base as production
