# Azure Functions Docker template

This repo contains a minimal Azure Function app template configured to run as a Docker container.

## Build

```bash
docker build -t myfunc .
```

## Run

```bash
docker run -p 8080:80 myfunc
```