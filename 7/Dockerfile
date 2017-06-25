FROM docker:17.05-git
MAINTAINER Stephen Shary <stephen.shary@gmail.com>

# Define commonly used variables
ENV DOCKER_VERSION 17.05
ENV COMPOSE_VERSION 1.14.0
ENV NODE_VERSION 7.2.1

# Install Java.
RUN \
  apk add --no-cache --update \
      curl \
      py-pip \
      nodejs-current=7.2.1-r1 && \
  pip install docker-compose==1.14.0 && \
  rm -rf ~/.cache && \
  apk del py-pip && \
  rm -rf /var/cache/apk/*