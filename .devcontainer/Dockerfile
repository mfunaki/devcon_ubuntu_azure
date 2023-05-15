FROM mcr.microsoft.com/devcontainers/base:jammy

# Allow GPG signing from inside of a container
RUN apt-get update && apt-get install gnupg2 -y

# Install Azure CLI
RUN curl -sL https://aka.ms/InstallAzureCLIDeb | bash
