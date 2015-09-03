FROM ubuntu:14.04
MAINTAINER Eveline Meyer floo+docker@devzone.ch
ENV REFRESHED_AT 2015-09-03
RUN apt-get update
RUN apt-get -y -q install nginx
RUN mkdir -p /var/www/html
ADD nginx/gloabl.conf /etc/nginx/conf.d/
ADD nginx/nginx.conf /etc/nginx/nginx.conf
EXPOSE 80


