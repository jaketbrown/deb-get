FROM --platform=linux/amd64 ubuntu:20.04 as builder


ADD deb-get /

RUN apt update 
RUN apt install -y lsb-release
#&& apt install -y curl
#RUN curl -sL https://raw.githubusercontent.com/wimpysworld/deb-get/main/deb-get
RUN install deb-get /usr/bin/

#FROM --platform=linux/amd64 ubuntu:20.04

#COPY --from=builder /deb-get /
#RUN ls -l
