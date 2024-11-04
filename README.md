# Monitoring Environment with Nginx, Prometheus, and Nginx Exporter

This project sets up a Docker environment to test the functionality and configuration of Nginx with Prometheus and Nginx Exporter.

## Project Contents

- **docker-compose.yml**: Defines Docker services for Nginx, Nginx Exporter, and Prometheus.
- **nginx.conf**: Custom Nginx configuration with the `stub_status` module enabled.
- **prometheus.yml**: Prometheus configuration to collect metrics from Nginx Exporter.

## Instructions

1. **Start Docker containers:**

   ```bash
   docker-compose up -d
