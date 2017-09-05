FROM  cyberdojofoundation/ubuntu-build-essential:17.04
LABEL maintainer=jon@jaggersoft.com

RUN apt-get update && apt-get install --yes nasm

RUN nasm -v | grep -q 2.12.02
