FROM php:5.6-fpm-alpine

RUN apk update && \
    apk upgrade

RUN apk add nginx

RUN rm -rf /var/cache/apk/*
