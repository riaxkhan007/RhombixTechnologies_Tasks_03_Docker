# DevOps Internship - Docker Project

This project is part of the DevOps internship at Rhombix Technologies.

## Project Overview
A simple Dockerized Nginx app to demonstrate containerization skills.

## Files
- `Dockerfile` - Builds Nginx container
- `app/index.html` - Simple HTML page

## How to Build
```bash
docker build -t devops-docker-project .
docker run -d -p 8080:80 devops-docker-project
