# Simple Docker-Compose example of Minio

- Running on traefik v2
- mounted to /data folder

## Setup

---

Copy env sample

```
cp .env.sample .env
```

Setup env vars

```
MINIO_ROOT_USER=minioadmin
MINIO_ROOT_PASSWORD=minioadmin
CONSOLE_HOST=minio-console.example.com
SERVER_HOST=minio.example.com
```

Start container

```
docker compose up -d
```

Visit console host and explore ✨
