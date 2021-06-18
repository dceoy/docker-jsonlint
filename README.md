docker-jsoinlint
================

Dockerfile for JSON Lint

[![CI to Docker Hub](https://github.com/dceoy/docker-jsonlint/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/dceoy/docker-jsonlint/actions/workflows/docker-publish.yml)

Docker image
------------

Pull the image from [Docker Hub](https://hub.docker.com/r/dceoy/jsonlint/).

```sh
$ docker image pull dceoy/jsonlint
```

Usage
-----

Validate a JSON file.

```sh
$ docker container run --rm -v ${PWD}:/wd -w /wd dceoy/jsonlint foo.json
```
