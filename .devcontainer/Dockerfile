FROM mcr.microsoft.com/devcontainers/python:3.11
RUN apt-get update && apt-get install -y --no-install-recommends curl git build-essential ca-certificates openssl wget && rm -rf /var/lib/apt/lists/*
# This line can be removed. Node.js installation should be handled via devcontainer features in devcontainer.json
# For example, add the following to the "features" section in devcontainer.json:
# "ghcr.io/devcontainers/features/node:1": {
#   "version": "20"
# }
WORKDIR /workspaces/open-notebook