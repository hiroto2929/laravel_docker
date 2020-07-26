FROM php:7-fpm
RUN apt-get update && apt-get install -y \
    vim \
    git
RUN docker-php-ext-install pdo_mysql
RUN apt-get install -y sudo
RUN sudo apt install php-mbstring php-xml php-json
RUN curl https://getcomposer.org/installer | php
RUN sudo mv composer.phar /usr/local/bin/composer
COPY --from=composer:latest /usr/bin/composer /usr/bin/compose