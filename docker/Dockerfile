FROM debian:stretch
LABEL maintainer="zdok Developers <dev@zdok.org>"
LABEL description="Dockerised ZdokCore, built from Travis"

RUN apt-get update && apt-get -y upgrade && apt-get clean && rm -fr /var/cache/apt/*

COPY bin/* /usr/bin/
