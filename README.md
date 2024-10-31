# Bones Game Project

## Description

A dice game implementation with Angular frontend and dual backend architecture (Java Spring Boot and Python Flask).

## Prerequisites

- Docker Desktop ([Download here](https://www.docker.com/products/docker-desktop/))
- Docker Compose (included with Docker Desktop)

## Quick Start

1. Create a `.env` file in the root directory with the following content:

MONGODB_URI=<mongodb-connection-string>
MONGODB_DATABASE=<database_name

2. Run the application:

docker-compose up

3. Access the applications:

- Frontend: http://localhost:4200
- Java Backend: http://localhost:8080
- Python Backend: http://localhost:8000

## Architecture

The project consists of three main components:

- Angular Frontend (Port 4200)
- Java Spring Boot Backend (Port 8080)
- Python Flask Backend (Port 8000)
