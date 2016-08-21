FROM ubuntu:14.04

MAINTAINER Gustavo Corrêa <gcajpa@gmail.com>

RUN apt-get update
RUN apt-get -y install curl
RUN curl -sL https://deb.nodesource.com/setup_4.x | sudo -E bash -
RUN apt-get -y install python build-essential nodejs git-core

RUN npm install pm2 -g