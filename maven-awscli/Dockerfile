FROM maven:3.6.0-jdk-8

RUN apt-get update && apt-get install -y \
    python \
    python-pip \
    python-dev \
 && pip install awscli \
 && apt-get clean
