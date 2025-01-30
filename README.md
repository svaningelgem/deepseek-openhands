# Local LLM Development Environment

A simple setup for running and testing large language models locally using Docker.

## What's Included

- **LiteLLM Proxy**: Handles communication with the language model
- **OpenHands**: Provides a web interface for testing and managing your AI models

## Quick Start

1. Make sure you have Docker and Ollama installed
2. Run `docker compose up`
3. Access:
    - OpenHands interface: http://localhost:3000
    - LiteLLM API: http://localhost:4000

## Configuration

- The setup uses the DeepSeek-R1 model by default
- Configuration files:
    - `docker-compose.yml`: Main setup file
    - `litellm.config.yml`: Model settings

## Need Help?

If things aren't working:
1. Check if Ollama is running
2. Make sure ports 3000 and 4000 are free
3. Look at the logs with `docker compose logs`