FROM ubuntu:24.04

ARG DEBIAN_FRONTEND=noninteractive

RUN apt-get update \
    && apt-get install -y --no-install-recommends \
        build-essential \
        cmake \
        ninja-build \
        gdb \
        git \
        ca-certificates \
        sudo \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /workspaces/vscode-docker
