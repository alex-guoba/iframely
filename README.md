# Iframely Docker

This is the docker version of [Iframely](https://iframely.com)'s APIs and HTML parsers.
It's a simple way to run Iframely on your own server.

## Usage

1. Prepare environment

```shell
cp ./config.local.js.SAMPLE ./config.local.js
```

2. Run docker

```shell
# Run
docker compose up -d

# Stop
docker compose down
```

## Install in dokploy project

See [dokploy.dokploy.yml](./docker-compose.dokploy.yml).
