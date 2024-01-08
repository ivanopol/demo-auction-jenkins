FROM jenkins/jenkins

USER root

RUN apk add --no-cache py-pip musl-dev python3-dev libffi-dev openssl-dev gcc libc-dev rust cargo \
    && pip3 install --upgrade pip \
    && pip3 install docker-compose

USER jenkins
