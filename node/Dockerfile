# DOCKER-VERSION 0.4.x
FROM ubuntu:12.10
MAINTAINER jden <jason@denizac.org>

# REPOS

RUN echo "deb http://archive.ubuntu.com/ubuntu precise main universe" > /etc/apt/sources.list
RUN echo "deb http://ppa.launchpad.net/chris-lea/node.js/ubuntu precise main" >> /etc/apt/sources.list
RUN gpg --ignore-time-conflict --no-options --no-default-keyring --secret-keyring /tmp/tmp.U6rnskPajB --trustdb-name /etc/apt/trustdb.gpg --keyring /etc/apt/trusted.gpg --primary-keyring /etc/apt/trusted.gpg --keyserver hkp://keyserver.ubuntu.com:80/ --recv 136221EE520DDFAF0A905689B9316A7BC7917B12
RUN apt-get update -y -q
RUN apt-get install nodejs