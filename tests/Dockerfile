FROM alpine:latest

RUN apk add --update openssl && \
    rm -rf /var/cache/apk/*

RUN openssl genrsa -out /etc/test.key