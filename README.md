# Docker images

[![Build Docker image](https://github.com/CatTheHacker/docker-images/workflows/Build%20Docker%20image/badge.svg)](https://github.com/CatTheHacker/docker-images/actions?query=workflow%3A%22Build+Docker+image%22)

## When updates will be applied to images

- A package that will be required for action(s) to work properly might be added/removed/changed
- Any maintainance that will be required due to:
  - Docker Hub
  - Quay
  - GitHub Container Registry
  - GitHub Actions
  - Act
- Performance and/or disk space improvements

## Images available

- [virtual-environments](github.com/catthehacker/virtual-environments) - GitHub Actions runner image containing all possible tools (image is extremely big, 20GB compressed, ~60GB extracted)
  - `quay.io/catthehacker/virtual-environments:ubuntu-20.04` - this image is updated manually due to amount of changes in [github.com/actions/virtual-environments](github.com/actions/virtual-environments)
  - more to come...
- `\linux\ubuntu\runner\Dockerfile` - used as base image for [github.com/catthehacker/act](https://github.com/catthehacker/act)
  - ghcr.io (GitHub Container Registry)
    - `ghcr.io/catthehacker/ubuntu:runner-16.04`
    - `ghcr.io/catthehacker/ubuntu:runner-18.04`
    - `ghcr.io/catthehacker/ubuntu:runner-20.04`
    - `ghcr.io/catthehacker/ubuntu:runner-latest`
  - quay.io (RedHat Container Registry)
    - `quay.io/catthehacker/ubuntu:runner-16.04`
    - `quay.io/catthehacker/ubuntu:runner-18.04`
    - `quay.io/catthehacker/ubuntu:runner-20.04`
    - `quay.io/catthehacker/ubuntu:runner-latest`
  - docker.io (DockerHub)
    - `catthehacker/ubuntu:runner-16.04`
    - `catthehacker/ubuntu:runner-18.04`
    - `catthehacker/ubuntu:runner-20.04`
    - `catthehacker/ubuntu:runner-latest`
- `\linux\ubuntu\act\Dockerfile` - image used in [github.com/nektos/act](https://github.com/nektos/act) as medium size image retaining compatibility with most actions while maintaining small size
  - ghcr.io (GitHub Container Registry)
    - `ghcr.io/catthehacker/ubuntu:act-16.04`
    - `ghcr.io/catthehacker/ubuntu:act-18.04`
    - `ghcr.io/catthehacker/ubuntu:act-20.04`
    - `ghcr.io/catthehacker/ubuntu:act-latest`
  - quay.io (RedHat Container Registry)
    - `quay.io/catthehacker/ubuntu:act-16.04`
    - `quay.io/catthehacker/ubuntu:act-18.04`
    - `quay.io/catthehacker/ubuntu:act-20.04`
    - `quay.io/catthehacker/ubuntu:act-latest`
  - docker.io (DockerHub)
    - `catthehacker/ubuntu:act-16.04`
    - `catthehacker/ubuntu:act-18.04`
    - `catthehacker/ubuntu:act-20.04`
    - `catthehacker/ubuntu:act-latest`
