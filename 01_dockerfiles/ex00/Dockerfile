FROM alpine

MAINTAINER Ltreu <ltreu@student.wethinkcode.co.za>

RUN apk update && \
    apk upgrade && \
    apk add vim

ENTRYPOINT vim

# How to build it?
# docker build -t ex00 .

# How to run it?
# docker run --rm -ti ex00