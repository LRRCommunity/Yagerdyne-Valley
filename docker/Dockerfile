FROM mono:6.6.0.161

ARG DEBIAN_FRONTEND=noninteractive

RUN apt-get update && apt-get install --no-install-recommends -y \
    imagemagick \
 && rm -rf /var/lib/apt/lists/* /tmp/*

WORKDIR /opt/stardew
COPY stardew-libs .
