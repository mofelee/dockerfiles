FROM mofe/ubuntu:latest
MAINTAINER Mofe Lee <mofe@me.com>

RUN apt-get update \
    && apt-get install nginx -y

EXPOSE 80 443
CMD ["nginx", "-g", "daemon off;"]
