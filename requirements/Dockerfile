# OmiX Navigator - base docker image
#
# VERSION 15.1

FROM ubuntu:14.04.3

MAINTAINER David Fazekas, fazekasda@gmail.com

RUN apt-get update -qq && apt-get upgrade -y && \
    apt-get install --no-install-recommends -y git-core \
    apt-get autoremove -y && apt-get clean && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
