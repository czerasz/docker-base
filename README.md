# Base Dockerfile


This repository contains **Dockerfile** of [Ubuntu](http://www.ubuntu.com/) for [Docker](https://www.docker.com/)'s [automated build](https://registry.hub.docker.com/u/czerasz/base/) published to the public [Docker Hub Registry](https://registry.hub.docker.com/).


## Base Docker Image

* [ubuntu:latest](https://registry.hub.docker.com/u/library/ubuntu/)


## Installation

1. Install [Docker](https://www.docker.com/)

2. Download [automated build](https://registry.hub.docker.com/u/czerasz/base/) from public [Docker Hub Registry](https://registry.hub.docker.com/):

        docker pull czerasz/base

    Alternatively, you can build an image from Dockerfile:

        docker build -t="czerasz/base" github.com/czerasz/docker-base

## Usage

    docker run -it --rm czerasz/base