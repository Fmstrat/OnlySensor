FROM ghcr.io/esphome/esphome

# From: https://github.com/esphome/esphome/blob/15180ee1e2f9f7254fa277c37379372dc2b43f0a/docker/Dockerfile#L162
RUN \
    rm -rf /esphome &&\
    git clone -b ld2450 https://github.com/hareeshmu/esphome.git /esphome &&\
    pip3 install --break-system-packages --no-cache-dir --no-use-pep517 -e /esphome