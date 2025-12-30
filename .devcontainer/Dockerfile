FROM mcr.microsoft.com/devcontainers/python:3.11
RUN apt-get update && apt-get install -y --no-install-recommends curl git build-essential ca-certificates openssl wget && rm -rf /var/lib/apt/lists/*
RUN curl -fsSL https://deb.nodesource.com/setup_20.x | bash - && apt-get update && apt-get install -y nodejs && rm -rf /var/lib/apt/lists/*
WORKDIR /workspaces/open-notebook