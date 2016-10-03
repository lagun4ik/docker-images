FROM mhart/alpine-node:6.7

RUN apk add --update --no-cache git nano bash
RUN apk add --update --no-cache python make g++ gcc
RUN npm i -g bower gulp node-gyp && mkdir /app

WORKDIR /app

CMD bash
