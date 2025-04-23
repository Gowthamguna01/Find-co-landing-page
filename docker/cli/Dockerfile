FROM serversideup/php:8.3-cli-alpine-v3.3.0 as base
USER root

RUN install-php-extensions http raphf  intl exif bcmath


FROM base as production
