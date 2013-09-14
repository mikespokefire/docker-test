FROM ubuntu:12.04
RUN echo "deb http://archive.ubuntu.com/ubuntu/ precise universe" >> /etc/apt/sources.list
RUN apt-get update

RUN apt-get install -y python-software-properties
RUN add-apt-repository ppa:nginx/stable

RUN apt-get update
RUN apt-get install -y nginx
