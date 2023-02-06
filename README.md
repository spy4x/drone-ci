# Docker Compose config for Drone CI

Run Drone CI in a Docker container with docker compose.

## Usage
1. Follow GitHub integration instructions at https://docs.drone.io/server/provider/github/
2. Fill .env file with your GitHub OAuth app credentials and generate other secret keys.
3. Run `docker-compose up -d` to start Drone CI.

## Known issues
- Drone Runner doesn't start up on MacOS - job is in pending state forever. Use Linux as a host instead.