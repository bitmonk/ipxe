FROM debian:bullseye

ENV DEBIAN_FRONTEND=noninteractive

RUN apt update && apt install -y \
  build-essential \
  gcc \
  liblzma-dev \
  isolinux \
  mkisofs

WORKDIR /src

ENTRYPOINT nice make


