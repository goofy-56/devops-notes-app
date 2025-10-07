# DevOps Notes App

Next.js + Express + PostgreSQL fullstack app.

## Features
- Containerized frontend and backend using Docker
- CI/CD with GitHub Actions + GHCR
- Kubernetes deployment manifests (Minikube-ready)
- Nginx reverse proxy for unified access

## Quick Start
```bash
docker compose up -d --build
```

## Deploy to Minikube
```bash
kubectl apply -f k8s/
minikube service notes-frontend
```
