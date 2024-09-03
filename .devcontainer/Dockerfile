FROM mcr.microsoft.com/devcontainers/rust:1-1-bullseye

# Install required dependencies and the GitHub CLI
RUN apt-get update -y && \
    apt-get install -y gh && \
    rm -rf /var/lib/apt/lists/*
