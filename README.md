### Docker
To run Gatus with Docker based on the Config.yaml file:

command:
```console
docker run -p 8080:8080 --mount type=bind,source="$(pwd)"/config.yaml,target=/config/config.yaml --name gatus twinproduction/gatus
```

