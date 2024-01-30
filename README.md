# jellyfin

Jellyfin + Docker Compose + make

## Requirements

- Docker
- Update the volumes inside the file `docker-compose.yml`, you should add your own media folders
- Update the hostname inside the same file (`chad.tv`)

## Quick Start

```sh
git clone https://gitlab.com/saulmendoza/jellyfin.git
cd jellyfin
docker-compose up -d

# or if you have make installed
make start
make help
```
