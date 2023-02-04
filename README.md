# Introduction

This is a simple setup to run [konga](https://pantsel.github.io/konga/) with a postgres database in docker using docker-compose.

# Usage

Pre requisites, must be installed:

* [docker](https://docs.docker.com/install/)
* [docker-compose](https://docs.docker.com/compose/install/)

## Start

```bash
$ docker-compose up -d
```

The konga web interface is available at [http://localhost:1337](http://localhost:1337).

## Stop

```bash
$ docker-compose down
```