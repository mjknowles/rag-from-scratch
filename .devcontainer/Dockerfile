#https://hub.docker.com/_/microsoft-devcontainers-anaconda
FROM mcr.microsoft.com/devcontainers/anaconda:3

RUN git config --global --add safe.directory /workspaces/rag-from-scratch
COPY requirements.txt .
RUN pip install -r requirements.txt && rm requirements.txt