# rattic-docker

[![](https://img.shields.io/docker/pulls/ptman/rattic.png)](https://hub.docker.com/r/ptman/rattic/)
[![](https://img.shields.io/docker/automated/ptman/rattic.png)](https://hub.docker.com/r/ptman/rattic/builds/)
[![](https://images.microbadger.com/badges/image/ptman/rattic.svg)](http://microbadger.com/images/ptman/rattic)

[Rattic](https://github.com/tildaslash/RatticWeb/)

# Quickstart

Note that this is not a production setup, but it is very close. Just change the
configuration a bit to you liking.

    docker-compose up
    # when it is up, open a new terminal and:
    docker-compose run rattic deploy
    docker-compose run rattic demosetup
    # Log in on http://localhost:8000 with user 'admin', password 'rattic'

# Configuration

Look at the env vars available in the `Dockerfile` and `entrypoint.sh`.
