FROM mcr.microsoft.com/devcontainers/python:3.12-bookworm
# EXPOSE 5000:5000
COPY .devcontainer/setup.sh ./
COPY requirements.txt ./
RUN ./setup.sh
