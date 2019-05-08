FROM alpine:3.9.3
 
LABEL maintainer="ivan.lagunovsky@gmail.com"

RUN apk upgrade --update --no-cache && \
    apk add --update --no-cache \
    ca-certificates \
    rsync \
    curl \
    openssh \
    shadow \
    bash && \
    \
    echo "http://dl-cdn.alpinelinux.org/alpine/edge/testing" >> /etc/apk/repositories && \
    apk add --update --no-cache lbzip2 && \
    \
    echo "http://dl-cdn.alpinelinux.org/alpine/v3.9/main" > /etc/apk/repositories && \
    echo "http://dl-cdn.alpinelinux.org/alpine/v3.9/community" >> /etc/apk/repositories
