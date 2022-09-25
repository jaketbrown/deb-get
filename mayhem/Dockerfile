FROM --platform=linux/amd64 ubuntu:20.04 as builder

ADD . /deb-get
WORKDIR /deb-get

RUN apt update && apt install -y curl
RUN curl -sL https://raw.githubusercontent.com/wimpysworld/deb-get/main/deb-get
RUN install deb-get /usr/bin/

FROM --platform=linux/amd64 ubuntu:20.04

