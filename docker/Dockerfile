FROM php:alpine

# install serverless
RUN apk add --update nodejs nodejs-npm \
    && npm install -g serverless

# install composer
RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer