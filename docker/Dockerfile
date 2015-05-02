FROM debian:wheezy

RUN apt-get update

RUN apt-get install -y build-essential \
                       libncurses5-dev \
                       libncursesw5-dev \
                       libreadline6-dev \
                       libdb5.1-dev \
                       libgdbm-dev \
                       libsqlite3-dev \
                       libssl-dev \
                       libbz2-dev \
                       libexpat1-dev \
                       liblzma-dev \
                       zlib1g-dev \
                       wget \
                       ca-certificates \
                       git \
                       libffi-dev \
                       libgeos-dev \
		       golang

RUN mkdir -p /home/go/src /home/go/pkg /home/go/bin

ENV GOPATH=/home/go
