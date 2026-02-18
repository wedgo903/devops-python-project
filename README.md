# DevOps Python Project

## Opis
Projekt DevOps integrujący:
- GitHub
- Docker (multi-stage build)
- Docker Compose
- GitHub Actions (CI)

Aplikacja: proste API w FastAPI.

## Uruchomienie lokalne

### 1. Budowa obrazu
docker build -t devops-api .

### 2. Uruchomienie
docker run -p 8000:8000 devops-api

### 3. Docker Compose
docker compose up --build

## Endpointy

GET /health
GET /hello
