FROM ubuntu:20.04

WORKDIR /usr/src/app

COPY curler.sh .
RUN apt-get update && apt-get -y install curl

ENTRYPOINT ["./curler.sh"]
