## 👋 Welcome to xbackbone 🚀

Lightweight file manager and sharing platform

## 📋 Description

Lightweight file manager and sharing platform

## 🚀 Services

- **xbackbone**: xbackbone/xbackbone:latest

## 📦 Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/xbackbone/main/docker-compose.yaml" -o compose.yml
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/xbackbone" ~/.local/srv/docker/xbackbone
cd ~/.local/srv/docker/xbackbone
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install xbackbone
```

## 🔧 Configuration

### Environment Variables

```shell
TZ=America/New_York
SERVICE_USER=1000
SERVICE_GROUP=1000
```

See `docker-compose.yaml` for complete list of configurable options.

## 🌐 Access

- **Web Interface**: http://172.17.0.1:8103

## 📂 Volumes

- `./volumes/config/xbackbone` - Data storage
- `./volumes/data/xbackbone` - Data storage

## 🔍 Logging

```shell
docker compose logs -f xbackbone
```

## 🛠️ Management

```bash
# Start services
docker compose up -d

# Stop services
docker compose down

# Update to latest images
docker compose pull && docker compose up -d

# View logs
docker compose logs -f

# Restart services
docker compose restart
```

## 📋 Requirements

- Docker Engine 20.10+
- Docker Compose V2+

## 🤝 Author

🤖 casjay: [Github](https://github.com/casjay) 🤖  
🦄 composemgr: [Github](https://github.com/composemgr) 🦄
