# CSV Scraper

This project allows users to upload a CSV file containing a list of URLs, and the system will scrape each URL, extract meta tags (title, description, keywords), and store the results.

## Features

- FastAPI for backend
- PostgreSQL for database
- Redis as a task queue
- Celery for asynchronous tasks
- Docker for containerization
- GitHub Actions for CI/CD
- Prometheus and Grafana for monitoring

## Getting Started

### Prerequisites

- Docker
- Docker Compose

### Running Locally

1. Build Docker images:
   ```sh
   docker-compose build
