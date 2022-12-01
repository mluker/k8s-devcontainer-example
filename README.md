# Sample devcontainer

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
