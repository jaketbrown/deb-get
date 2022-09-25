FROM --platform=linux/amd64 ubuntu:20.04 as builder

ADD . /deb-get
WORKDIR /deb-get

RUN apt install curl
RUN curl -sL https://raw.githubusercontent.com/wimpysworld/deb-get/main/deb-get | sudo -E bash -s install deb-get

FROM --platform=linux/amd64 ubuntu:20.04

