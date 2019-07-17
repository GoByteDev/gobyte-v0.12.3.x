FROM debian:stretch
LABEL maintainer="GoByte Developers <dev@dash.org>"
LABEL description="Dockerised GoByte Core, built from Travis"

RUN apt-get update && apt-get -y upgrade && apt-get clean && rm -fr /var/cache/apt/*

COPY bin/* /usr/bin/
