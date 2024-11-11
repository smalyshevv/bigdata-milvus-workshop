FROM ubuntu:20.04 AS build_base

ENV DEBIAN_FRONTEND noninteractive

RUN apt update && apt install -y tcl

RUN apt-get update -y \
    && apt-get install -y python3-pip

RUN pip3 install pandas pymilvus==2.3.0 lightfm notebook