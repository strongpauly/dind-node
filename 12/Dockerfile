FROM docker

# Define commonly used variables
ENV NODE_VERSION 12

# Install Node.
RUN \
  apk add --no-cache --update \
      curl \
      py-pip \
      nodejs=12 && \
  rm -rf ~/.cache && \
  apk del py-pip && \
  rm -rf /var/cache/apk/*
