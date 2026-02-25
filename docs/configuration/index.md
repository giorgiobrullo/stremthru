# Configuration

StremThru is configured using environment variables.

## Setting Environment Variables

**Docker:**

```sh
docker run -e STREMTHRU_AUTH=user:pass muniftanjim/stremthru
```

**Docker Compose** (using `.env` file):

```sh
STREMTHRU_AUTH=user:pass
```

**From source:**

```sh
export STREMTHRU_AUTH=user:pass
make run
```
