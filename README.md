# docker-buildx-bake-demo
Docker Buildx Bake Demo

## Example commands

```bash
# Build docker images
$ docker buildx bake -f docker-bake.dev.hcl db webapp-release

# To push result images into registry
$ docker buildx bake -f docker-bake.dev.hcl --push db webapp-release
```

See images at Docker Hub https://hub.docker.com/r/xianpengshen/docker-buildx-bake-demo
