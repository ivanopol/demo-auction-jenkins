FROM jenkins/jenkins:alpine-jdk21

USER root

RUN apk add --no-cache py-pip musl-dev python3-dev libffi-dev openssl-dev gcc libc-dev rust cargo make gettext
RUN apk add docker-compose

USER jenkins
