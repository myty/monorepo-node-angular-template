ARG VARIANT=16-bullseye

FROM mcr.microsoft.com/vscode/devcontainers/javascript-node:0-${VARIANT}

RUN sudo apt-get update && sudo apt-get install yarn

RUN su node -c "npm install -g @feathersjs/cli"