FROM nginx:latest

RUN apt-get update -y &&\
    apt-get install nano -y
ADD ./index.html ./usr/share/nginx/html

EXPOSE 80
