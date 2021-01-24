FROM php:7.3-apache 

RUN pecl install mongodb \
    &&  echo "extension=mongo.so" > /usr/local/etc/php/conf.d/mongo.ini