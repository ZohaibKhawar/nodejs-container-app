# nodejs-container-app

Lab 9 — a Node.js (Express) app containerized with Docker, built and pushed to Docker Hub by a GitHub Actions CI/CD pipeline.

## Run it

```
docker build -t nodejs-container-app .
docker run -p 3000:3000 nodejs-container-app
```

Then open http://localhost:3000.
