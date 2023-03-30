# docker-hub-pusher

## Steps

1. Build Dockerfile
2. Tag it
3. Push to Docker Hub
4. ???
5. Profit!!!

## Requirements

Add the following Github Secrets to your repo:

- DOCKER_HUB_USERNAME
- DOCKER_HUB_TOKEN

Change the following `env` variable for your image name in `.github/workflows/docker-build-push.yml`:

- IMAGE_NAME
