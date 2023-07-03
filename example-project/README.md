# Example project

To run the project inside a local build of the devcontainer for testing, edit the `.devcontainer/devcontainer.json` file to point at a local Docker image instead.

## Local

```json
{
  "image": "devcontainer:latest"
}
```

## Remote

```json
{
  "image": "ghcr.io/example-pipeline/devcontainer:main"
}
```
