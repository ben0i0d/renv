FROM debian:bookworm-slim

SHELL ["/bin/bash", "-o", "pipefail", "-c"]

USER root

# Configure environment
ENV DEBIAN_FRONTEND=noninteractive 

RUN sed -i 's/deb.debian.org/mirrors.ustc.edu.cn/g' /etc/apt/sources.list.d/debian.sources 
