# Dockerized Flask Application with GitHub Actions CI/CD

## Overview

This project demonstrates how to containerize a Flask web application
using Docker and automate the Docker build process using GitHub Actions.

## Architecture

Developer
   ↓
GitHub Repository
   ↓
GitHub Actions
   ↓
Docker Build
   ↓
Docker Image
   ↓
Containerized Flask Application

## Technologies

- Python
- Flask
- Docker
- Git
- GitHub
- GitHub Actions
- Linux

## Features

- Flask web application
- Docker containerization
- Automated Docker image build
- CI pipeline using GitHub Actions
- Reproducible application environment

## Run Locally

```bash
docker build -t flask-app .
docker run -d -p 5000:5000 --name flask flask-app
