FROM buildpack-deps:jessie

RUN apt-get update && apt-get install -y --no-install-recommends genisoimage libiberty-dev libbfd-dev && rm -rf /var/lib/apt/lists/*

VOLUME /ipxe
WORKDIR /ipxe/src
