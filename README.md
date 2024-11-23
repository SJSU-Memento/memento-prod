# Memento Production Configuration

This repository contains the configuration files for the production environment of the Memento project.

## Deployment

First create the `.env` file with the following content:

- `OPENAI_API_KEY`
- `GEOAPIFY_API_KEY`

Then run the following command:

```bash
docker compose up -d
```

## Firmware

To setup the firmware, follow the instructions in the [firmware README](firmware/README.md).
