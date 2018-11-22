FROM alpine:3.8

MAINTAINER ivan@lagunovsky.com

RUN echo "http://dl-cdn.alpinelinux.org/alpine/edge/community" >> /etc/apk/repositories && \
    echo "http://dl-cdn.alpinelinux.org/alpine/edge/main" >> /etc/apk/repositories && \
    echo "http://dl-cdn.alpinelinux.org/alpine/edge/testing" >> /etc/apk/repositories && \
    \
    apk upgrade --update --no-cache && \
    apk add --update --no-cache \
    ca-certificates \
    rsync \
    curl \
    openssh \
    shadow \
    bash \
    lbzip2
