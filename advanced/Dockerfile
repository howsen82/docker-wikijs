FROM node:20
LABEL maintainer "steven@gmail.com"

RUN apt-get update && \
    apt-get install -y bash curl git python make g++ nano openssh-server gnupg && \
    mkdir -p /wiki

WORKDIR /wiki

ENV dockerdev 1
ENV DEVDB postgres

EXPOSE 3000

CMD ["tail", "-f", "/dev/null"]