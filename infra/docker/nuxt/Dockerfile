FROM node:18-slim

ENV TZ Asia/Tokyo

#https://blog.mechill.jp/tech/230616_nuxt3-docker-error/
WORKDIR /front

RUN apt-get update \
    && apt-get install -y \
    git \
    vim
