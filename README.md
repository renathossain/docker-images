# docker-images

Build and publish all docker images I need for projects.

Build Commands:

- `docker build -f Dockerfile.ubuntu -t renathossain/mcbr-ubuntu-ci .`

Publish Commands:

- `docker login`
- `docker push renathossain/mcbr-ubuntu-ci:latest`
