## Ubuntu Dockerfile Fork for Precise



### Base Docker Image

* [ubuntu:12.04](https://registry.hub.docker.com/u/library/ubuntu/)


### Installation

1. Install [Docker](https://www.docker.com/).

2. Download [automated build](https://registry.hub.docker.com/u/dockerfile/ubuntu/) from public [Docker Hub Registry](https://registry.hub.docker.com/): `docker pull dockerfile/ubuntu`

   (alternatively, you can build an image from Dockerfile: `docker build -t="dockerfile/ubuntu" github.com/dockerfile/ubuntu`)


### Usage

    docker run -it --rm chrisduong/Dockerfile-ubuntu-12.04
