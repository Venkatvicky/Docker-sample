# Sample Docker + Jenkins + Nexus OSS Project

This is a sample project that:

- Uses a simple `index.html` file served by Nginx.
- Builds a Docker image using a `Dockerfile`.
- Pushes the image to a Nexus OSS Docker repository using a Jenkins pipeline.

## Jenkins Pipeline Overview

1. Build Docker image
2. Push to Nexus OSS Docker hosted repo
