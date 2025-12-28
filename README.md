# About GitLab CI Training

This project demonstrates modern DevOps practices with a focus on Docker containerization and automated deployment workflows using GitLab CI/CD. 

## Key Features

- **Multi-stage Docker builds** for optimized container images
- **Nginx-based web serving** with custom configuration
- **Automated CI/CD pipelines** using GitLab CI
- **Infrastructure as Code** practices
- **Production-ready deployment** strategies

## Technology Stack

- **Docker**:  Multi-stage builds for efficient containerization
- **Nginx**: High-performance web server (Alpine-based)
- **GitLab CI**: Continuous Integration and Deployment
- **Ubuntu & Alpine Linux**: Base images for different stages

## Use Cases

This repository serves as a practical training resource for:
- Learning Docker multi-stage builds
- Implementing GitLab CI/CD pipelines
- Deploying containerized web applications
- Understanding DevOps best practices

## Project Structure

The project includes a Dockerfile implementing a two-stage build process:
1. **Stage 1 (files)**: Clones static website content from a Git repository
2. **Stage 2 (nginx)**: Serves the content using a lightweight Nginx Alpine image

This approach minimizes the final image size while maintaining a clean separation of concerns.

---

**Maintainer**: TCHASSEM ANSELME  
**Purpose**: DevOps Training & Best Practices Demonstration
