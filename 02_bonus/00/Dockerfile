FROM debian

MAINTAINER Ltreu <ltreu@student.wethinkcode.co.za>

RUN apt-get update && apt-get install -y cowsay fortune lolcat

ENTRYPOINT /usr/games/fortune | /usr/games/cowsay | /usr/games/lolcat

# How to build it?
# docker build -t a00 .

# How to run it?
# docker run --rm -ti a00

# found:
# https://gist.github.com/nucliweb/da7cff954032bdc685f1