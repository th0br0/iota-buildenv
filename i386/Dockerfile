# ubuntu 17.10 i386
FROM ubuntu@sha256:890e96e274fc1a4f8186b472945e5d60a422a7589330abb971990e186596de6d

RUN apt-get update &&  apt-get install  -y \
    automake \
    build-essential \
    wget \
    cmake \ 
    unzip \
    zip \
    curl \
    doxygen \
    libssl-dev \
    openssl \
    xxd \
    ccache \
    git \
    graphviz \
    python3-dev \
    python3-numpy \
    openjdk-8-jdk \
    python \
    gcc \
    g++ \
 && apt-get clean \
 && rm -rf /var/lib/apt/lists/*
