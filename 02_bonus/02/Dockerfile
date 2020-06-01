FROM ubuntu

MAINTAINER Ltreu <ltreu@student.wethinkcode.co.za>

RUN apt-get update && apt-get install -y apt-utils && apt-get upgrade -y && apt-get install -y nodejs npm git vim emacs

RUN npm install yarn --global && npm install npm --global

# How to build it?
# docker build -t a02 .

# How to run it?
# docker run --rm -ti a02