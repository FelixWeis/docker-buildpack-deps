FROM buildpack-deps:stretch

RUN apt-get update && apt-get install -y --no-install-recommends \
        libboost-all-dev \
    && rm -rf /var/lib/apt/lists/*
