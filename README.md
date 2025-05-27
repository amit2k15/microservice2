# mysqld-microservice

A simple microservice running MySQL (`mysqld`) designed to be deployed on an OKD (OpenShift) cluster.

## Deployment Steps

1. **Build Docker Image**
   ```bash
   docker build -t <your-dockerhub-username>/mysqld-microservice .
   docker push <your-dockerhub-username>/mysqld-microservice
