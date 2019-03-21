FROM circleci/node:8.11.2

RUN sudo apt-get update && sudo apt-get install -y \
    python \
    python-pip \
    python-dev \
 && sudo pip install awscli \
 && sudo apt-get clean \
 && sudo npm install -g gitbook-cli \
 && gitbook help
