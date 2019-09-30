# Docker Flask

A portable flask app docker image.

## Getting started

To install and run on your local machine [Docker](https://www.docker.com/products/docker-desktop) is required.

## Install
```bash
git clone git@github.com:shektor/docker-flask.git
cd docker-flask
docker build --tag docker-flask
```

## Run
```bash
docker run -p 80:8000 docker-flask
```
Visit [localhost:80](http://localhost:80/)
