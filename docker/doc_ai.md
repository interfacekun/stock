---
title: docker Root Folder Documentation
summary: Docker container configuration and orchestration directory
tags: [docker, containers, deployment, orchestration]
---

# docker Root Folder

## Description
This is the Docker container configuration and orchestration directory containing all files necessary for containerizing the stock trading platform. The docker folder houses Dockerfile definitions, compose configurations, and build scripts for deploying the application in containerized environments.

## Contents Overview
- .dockerignore: Docker ignore configuration
- .gitignore: Git ignore configuration
- build.sh: Build script for Docker images
- docker-compose.yml: Docker Compose configuration file
- Dockerfile: Main Dockerfile for building application image

## Key Components
- `Dockerfile`: Defines the application container image
- `docker-compose.yml`: Orchestrates multi-container deployments
- `build.sh`: Automation script for building Docker images

## Subdirectories Index
 - `.dockerignore`: .dockerignore file
 - `.gitignore`: .gitignore file
 - `build.sh`: build.sh file
 - `docker-compose.yml`: docker-compose.yml file
 - `Dockerfile`: Dockerfile file