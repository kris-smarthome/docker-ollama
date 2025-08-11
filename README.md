# docker-ollama

Services:
- Ollama
- Open web UI

## usage
Clone this repository to your local machine, edit the config file to match your environment, and run docker compose.

```bash
git clone https://github.com/kris-smarthome/docker-ollama.git ollama/
cd ollama
nano .env
docker compose up -d
```

> [!NOTE]
> Create the traefik network before deploying this stack, if it doesn't already exist: `docker network create -d bridge traefik`. 
> Connected to the N8N network for simplicity, remove if not needed or N8N is on a separate host.