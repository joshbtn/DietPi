FROM debian:bookworm as build

RUN apt-get update && apt-get install -y \
    binfmt-support \
    build-essential \
    cmake \
    fdisk \
    git \
    libboost-all-dev \
    libssl-dev \
    libzmq3-dev \
    parted \
    pkg-config \
    python3-dev \
    python3-pip \
    qemu-user-static \
    systemd-container \
    xz-utils