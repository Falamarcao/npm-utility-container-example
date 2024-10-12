# Utility Containers

We can use a docker container to run commands and reflect changes on local host.

```sh
    docker compose run --rm npm init
    docker compose run --rm npm install
```

Note: `npm` is the name of the container, and we are appending a command `init` or `install` to the ENTRYPOINT command defined on the [Dockerfile](./Dockerfile).
