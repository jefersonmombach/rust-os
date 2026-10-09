FROM mcr.microsoft.com/devcontainers/rust:1-1-bookworm

RUN apt-get update \
    && apt-get install -y --no-install-recommends \
        qemu-kvm \
        qemu-system-gui \
        libvirt-daemon-system \
        libvirt-clients \
        bridge-utils \
        virt-manager \
    && rm -rf /var/lib/apt/lists/*
