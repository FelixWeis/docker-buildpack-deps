FROM buildpack-deps:jessie

RUN apt-get update && apt-get install -y --no-install-recommends \
		cmake \
		libboost-all-dev \
	&& rm -rf /var/lib/apt/lists/*
