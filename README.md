# Go Dev Container

Read readme in the parent repo - <https://github.com/qdm12/godevcontainer>

## Build this image

```bash
docker build -t yehors/go-devcontainer:1.20 -f alpine.Dockerfile .
```

## Push to Docker Hub

```bash
docker login

docker push yehors/go-devcontainer:1.20
```

## Clean up

```bash
docker system prune
```
