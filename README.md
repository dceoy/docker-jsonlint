docker-jsoinlint
================

Dockerfile for JSON Lint

Docker image
------------

Pull the image from [Docker Hub](https://hub.docker.com/r/dceoy/jsonlint/).

```sh
$ docker pull dceoy/jsonlint
```

Usage
-----

Validate a JSON file.

```sh
$ docker container run --rm -v ${PWD}:/wd -w /wd dceoy/jsonlint foo.json
```
