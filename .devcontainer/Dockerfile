FROM mcr.microsoft.com/devcontainers/python:3.12

# gettext: msgfmt など compilemessages に必要
RUN apt-get update \
 && apt-get install -y --no-install-recommends gettext \
 && apt-get clean \
 && rm -rf /var/lib/apt/lists/*
