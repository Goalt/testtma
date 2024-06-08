FROM mcr.microsoft.com/vscode/devcontainers/typescript-node:0-16-bullseye

RUN apt update
RUN apt install -y git cmake make g++ libssl-dev

# Install eslint typescript expo
RUN npm install -g npm@9.6.7
RUN npm install -g eslint typescript expo-cli

CMD /bin/sh -c "while sleep 86000; do :; done"
