FROM php:7.0-apache
RUN apt-get update && \
  docker-php-ext-install pdo_mysql mysqli mbstring
RUN a2enmod ssl && \
  a2ensite default-ssl

EXPOSE 80 443

ENTRYPOINT service apache2 start && tail -f /dev/null