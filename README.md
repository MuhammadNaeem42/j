
# Final Project 2

This project is containerized using Docker and can be run with Docker Compose. The API documentation will be available at `http://localhost:8000/docs`.

## Prerequisites

Make sure you have the following installed:
- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Quick Start

### 1. Clone the repository and navigate to the project directory:

```bash
cd final-project-2
```
## 2. Build the Docker images:
```bash
docker compose build
```
## 3. Start the application in detached mode:

```bash
docker compose up -d
```
## 4. Access the API Documentation:
Once the application is running, open your browser and go to:

```bash
http://localhost:8000/docs
```
## 5. Stop the Application
To stop the application, run:

```bash
docker compose down
```
### Troubleshooting
If you encounter any issues, ensure that Docker and Docker Compose are properly installed and running.
To view logs, use:

```bash
docker compose logs
```
