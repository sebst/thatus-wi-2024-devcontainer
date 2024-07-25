```bash
docker build -t testdevc . --progress=plain --no-cache
docker system prune -a
docker pull ghcr.io/sebst/thatus-wi-2024-devcontainer:latest
```

```bash
docker run it --rm testdevc bash
```