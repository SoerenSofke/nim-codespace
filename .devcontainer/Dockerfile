FROM mcr.microsoft.com/devcontainers/universal:2

RUN curl https://nim-lang.org/choosenim/init.sh -sSf | sh -s -- -y
RUN curl -L https://github.com/nim-lang/langserver/releases/download/v1.12.0/nimlangserver-linux-amd64.tar.gz | tar -xz -C ~/.nimble/bin

ENV PATH="~/.nimble/bin:$PATH"
