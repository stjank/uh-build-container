FROM debian:13.4

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
        libstdc++-14-dev \
        libicu-dev \
        libcurl4-openssl-dev \
        git \
        ccache      && \
    rm -rf /var/lib/apt/lists/*

