FROM mofe/ubuntu:latest
MAINTAINER Mofe Lee <mofe@me.com>

RUN apt-get update \
    && apt-get install -y libssl-dev build-essential wget python python-dev python-pip python-virtualenv \
    && wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.31.0/install.sh | bash \
    && . /root/.bashrc \
    && nvm install 4
