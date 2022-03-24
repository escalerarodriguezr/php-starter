# PHP Starter + Docker Boilerplate

## What is this?
This is a PHP starter project which includes `Docker configuration`.

It contains Open API v3 documentation
![Endpoints](./doc/endpoints.png)

## Usage /app
- `make build` to build the docker environment
- `make run` to spin up containers
- `make restart` to stop and start containers
- `make prepare` to install dependencies
- `make generate-ssh-keys` to generate JWT certificates
- `make ssh-be` to access the PHP container bash
- `make tests` to runt the test suite

## Usage /doc
- `make build` to build the docker environment
- `make run` to spin up containers
- Navigate to `http://localhost:2500/index.html` to check the Open API v3 documentation and testing endpoints
- `make restart` to stop and start containers

## Stack:
- `NGINX 1.19` container
- `PHP 8.0.6 FPM` container
- `MariaDB 10.7.1` container + `volume`

## Contributing
Feel free to clone, fork or PR this repo
