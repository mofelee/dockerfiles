FROM mofe/ubuntu:latest
MAINTAINER Mofe Lee <mofe@me.com>

RUN apt-get update \
    && apt-get install nginx -y

ENTRYPOINT ["service", "nginx"]
CMD ["start"]
