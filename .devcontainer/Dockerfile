FROM mcr.microsoft.com/vscode/devcontainers/base:ubuntu

# Install Julia
RUN apt-get update && \
    apt-get install -y wget && \
    wget https://julialang-s3.julialang.org/bin/linux/x64/1.6/julia-1.6.3-linux-x86_64.tar.gz && \
    tar -xvzf julia-1.6.3-linux-x86_64.tar.gz -C /usr/local --strip-components=1 && \
    rm julia-1.6.3-linux-x86_64.tar.gz

# Install Python
RUN apt-get install -y python3-pip
