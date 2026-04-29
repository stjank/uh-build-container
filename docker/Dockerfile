FROM ubuntu:26.04

RUN apt update && \
    apt install -y \
        cmake   \
        clang   \
        ninja-build \
        libpq-dev \
        postgresql \
        liblmdb++-dev \
        protobuf-compiler-grpc \
        libprotoc-dev \
        libgrpc++-dev \
        libgrpc-dev \
        libboost-all-dev \
        libstdc++-16-dev \
        libicu-dev \
        git \
        ccache      && \
    rm -rf /var/lib/apt/lists/*

