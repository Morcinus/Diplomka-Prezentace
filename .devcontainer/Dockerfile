FROM ubuntu:24.04

ENV DEBIAN_FRONTEND=noninteractive

# Base utilities and TeX stack for CTU FIT presentation development.
RUN apt-get update && apt-get install -y --no-install-recommends \
    apt-utils \
    ca-certificates \
    git \
    openssh-client \
    procps \
    biber \
    chktex \
    latexmk \
    make \
    python3-pkg-resources \
    python3-pygments \
    texlive-bibtex-extra \
    texlive-extra-utils \
    texlive-fonts-extra \
    texlive-fonts-recommended \
    texlive-lang-czechslovak \
    texlive-lang-english \
    texlive-latex-base \
    texlive-latex-extra \
    texlive-latex-recommended \
    texlive-pictures \
    texlive-xetex \
    && apt-get clean -y \
    && rm -rf /var/lib/apt/lists/*

ENV DEBIAN_FRONTEND=dialog \
    LANG=C.UTF-8 \
    LC_ALL=C.UTF-8
