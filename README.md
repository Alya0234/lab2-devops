# Lab 2: Containerization, Docker Compose, and Kubernetes Deployment

This repository contains the implementation artifacts, configuration manifests, and execution logs for Lab 2.

---

## Table of Contents
1. [Docker Image Build & Container Management](#1-docker-image-build--container-management)
2. [Multi-Container Orchestration with Docker Compose](#2-multi-container-orchestration-with-docker-compose)
3. [Kubernetes Cluster Setup & Manifest Deployment](#3-kubernetes-cluster-setup--manifest-deployment)
4. [Deployment Strategies & Validation](#4-deployment-strategies--validation)

---

## 1. Docker Image Build & Container Management

### Build Docker Image
```bash
docker build -t lab2-web:v1 ./docker