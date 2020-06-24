FROM docker

# Install Node.
RUN \
  apk add --no-cache --update \
  curl \
  py-pip \
  nodejs && \
  rm -rf ~/.cache && \
  apk del py-pip && \
  rm -rf /var/cache/apk/*
