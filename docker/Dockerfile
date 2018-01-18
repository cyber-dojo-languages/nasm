FROM  cyberdojofoundation/ubuntu-build-essential:18.04
LABEL maintainer=jon@jaggersoft.com

RUN apt-get update && apt-get install --yes nasm

RUN nasm -v | grep -q 2.13.02
