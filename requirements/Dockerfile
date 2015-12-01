# OmiX Navigator - base docker image
#
# VERSION 15.1

FROM ubuntu:14.04.3

MAINTAINER David Fazekas, fazekasda@gmail.com

RUN apt-get update -qq
RUN apt-get upgrade -y
RUN apt-get install --no-install-recommends -y git-core
RUN apt-get autoremove -y
RUN apt-get clean
RUN rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
