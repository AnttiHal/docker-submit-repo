FROM ubuntu:20.04

WORKDIR /usr/src/app

RUN apt-get update && apt-get install -y  curl

COPY file.sh .

RUN chmod +x file.sh
CMD ./file.sh
