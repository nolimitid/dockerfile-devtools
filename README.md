## Ubuntu Dockerfile


This repository contains **Dockerfile** of `NoLimit Indonesia Development Tools` for [Docker](https://www.docker.com/)'s [automated build](https://registry.hub.docker.com/u/nolimitid/devtools/) published to the public [Docker Hub Registry](https://registry.hub.docker.com/).


### Base Docker Image

* [ubuntu:14.04](https://registry.hub.docker.com/u/library/ubuntu/)


### Installation

1. Install [Docker](https://www.docker.com/).

2. Download [automated build](https://registry.hub.docker.com/u/nolimitid/devtools/) from public [Docker Hub Registry](https://registry.hub.docker.com/): `docker pull nolimitid/devtools`

   (alternatively, you can build an image from Dockerfile: `docker build -t="nolimitid/devtools" github.com/nolimitid/dockerfile-devtools`)


### Usage

    docker run -d -p 27017:27017 --name devtools nolimitid/devtools
