FROM ubuntu:15.10

RUN apt-get update -y && apt-get install -y \
    git \
    python-pip \
    python-dev \
    nodejs \
    npm \
    wget \
    curl

RUN npm -g install n
RUN n latest

RUN pip install --upgrade pip
RUN pip install --no-cache-dir numpy pandas
