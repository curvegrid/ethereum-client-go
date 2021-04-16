# ethereum-client-go

This repository contains a Github Action workflow that automatically builds [ethereum/go-ethereum](https://github.com/ethereum/go-ethereum) docker images for both amd64 and arm64 architectures when a new release is made. This was created because the official Docker Hub repo ([ethereum/client-go](https://hub.docker.com/r/ethereum/client-go/)) lacks of arm64 docker images.

Docker images are available in the [curvegrid/ethereum-client-go](https://hub.docker.com/r/curvegrid/ethereum-client-go/) docker repository.
