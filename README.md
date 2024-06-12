# Mysfits

This is a simple Flask application for demonstration purposes.

## Dockerfile

The `Dockerfile.v3` sets up the application to run using Python 3.8-slim, installs Flask, and copies the application code into the container.

## Workflow

The GitHub Actions workflow `.github/workflows/build-and-deploy.yml` automates the build and deployment process using Kaniko and ECS Fargate.