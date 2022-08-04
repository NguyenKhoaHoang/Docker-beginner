FROM nginx:latest

RUN apt-get update

RUN apt-get install -yqq telnet vim curl

RUN rm -rf /etc/nginx/conf.d/*

COPY ./mysite.conf /etc/nginx/conf.d

WORKDIR /var/www