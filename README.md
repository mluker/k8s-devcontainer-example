# Sample devcontainer

## Introduction

This repository is set up for development with [GitHub Codespaces](https://docs.github.com/en/codespaces/setting-up-your-project-for-codespaces/introduction-to-dev-containers) and VS Code [Dev Containers](https://code.visualstudio.com/docs/remote/containers).


## Included Utilities

- Docker-in-Docker (with Docker Compose v2 support)
- protobuf compiler
- Helm
- KinD (Kubernetes in Docker)
- kubectl
- Azure CLI

## What now?
Fire up the devcontainer

<img src="./media/devcontainer.png" height="300" />

Once it has started, from the command line run

```
kind cluster create
```

You now have a kubernetes cluster running in Kind. Interact with it using kubectl commands.
