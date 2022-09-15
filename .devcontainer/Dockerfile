FROM python:3.9.13-slim-bullseye

RUN apt update && apt install -y git ssh && apt clean
RUN adduser --home /home/vscode --shell /bin/bash --uid 1000 vscode

WORKDIR /workspace
VOLUME [ "/workspace" ]