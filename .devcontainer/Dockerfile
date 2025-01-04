# Base image: Node.js 18 on Debian (from the official Dev Containers library)
FROM mcr.microsoft.com/devcontainers/typescript-node:1-22-bookworm

# Install AWS CLI v2 (optional but useful if you want to interact with AWS from the container)
RUN apt-get update && apt-get install -y unzip curl && \
    curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "/tmp/awscliv2.zip" && \
    unzip /tmp/awscliv2.zip -d /tmp && \
    /tmp/aws/install && \
    rm -rf /tmp/awscliv2.zip /tmp/aws && \
    apt-get clean -y && rm -rf /var/lib/apt/lists/*
