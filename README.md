# Snaparser Docker Compose

This repository has example files for easily running
the snaparser server and web app using docker compose.

# Usage

## Using docker images

```sh
$ git clone https://github.com/vanillaiice/snaparser-docker-compose
$ cd snaparser-docker-compose
$ docker compose up
# or run it as a daemon
$ docker compose up -d
# stop the containers
$ docker compose down
```

## Build images

```
$ git clone https://github.com/vanillaiice/snaparser-docker-compose
$ cd snaparser-docker-compose
$ docker compose -f docker-compose-build.yml up -d --build
```

# Author

vanillaiice

# Licence

BSD-3-Clause
