FROM node:8

MAINTAINER Ilya Mochalov <chrootsu@gmail.com>

RUN apt-get update \
	&& apt-get install -y paxctl \
	&& paxctl -Cm /usr/local/bin/node \
	&& rm -rf /var/lib/apt/lists/*
