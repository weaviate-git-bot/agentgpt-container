# agentgpt-container

This repository contains code to containerize [AgentGPT](https://github.com/reworkd/AgentGPT) using Docker.

## Contents

- `Dockerfile` - Builds the Docker image with AgentGPT and dependencies
- `entrypoint.sh` - Startup script to launch the AgentGPT services
- `config/` - Configuration files mounted into the container
- `scripts/` - Helper scripts
  - `build.sh` - Builds the Docker image
  - `start.sh` - Starts the container
  - `logs.sh` - Views the container logs

