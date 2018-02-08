FROM  cyberdojofoundation/ubuntu-build-essential:18.04
LABEL maintainer=jon@jaggersoft.com

RUN apt-get update && apt-get install --yes nasm

COPY version.txt /tmp
RUN bash --version | grep -f /tmp/version.txt
