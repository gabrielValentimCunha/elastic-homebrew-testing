# Local Elastic Stack (Docker)

Spin up Elasticsearch + Kibana locally using Docker Compose.

## Requirements
- Docker Desktop (with Compose v2)
- Ports `9200` (Elasticsearch) and `5601` (Kibana) available
- An `.env` file in this repo (already present)

## Quick Start

```bash
# start
docker compose up -d

# check containers
docker compose ps

# follow logs (Ctrl+C to stop following)
docker compose logs -f elasticsearch
docker compose logs -f kibana
