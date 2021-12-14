FROM ubuntu:latest

RUN apt update
RUN apt install nginx

RUN mkdir -p /var/www/site

COPY . index.html /var/www/site/index.html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
