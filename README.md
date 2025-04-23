# Build-CI-CD-Pipeline
# CI/CD Pipeline using GitHub Actions

## Features
- On code push to `main`:
  - Runs PyTest tests
  - Builds Docker image
  - Pushes image to Docker Hub

## Setup

1. Add your DockerHub credentials as GitHub Secrets:
   - `DOCKER_USERNAME`
   - `DOCKER_PASSWORD`

2. Push code to `main` branch to trigger the workflow.

3. Visit DockerHub to verify your image has been pushed.
