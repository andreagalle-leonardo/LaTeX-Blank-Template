FROM mcr.microsoft.com/devcontainers/base:ubuntu-20.04

RUN apt-get update && apt-get install -y \
    texlive \
    texlive-latex-extra \
    texlive-fonts-recommended \
    texlive-lang-italian \
    pandoc \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*