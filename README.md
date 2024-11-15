# Multi-Container Web Application

This project demonstrates the deployment of a multi-container web application using Docker and Kubernetes. It includes multiple microservices organized in separate containers and deployed on **Google Cloud** using **Kubernetes** for container orchestration. This application is ideal for learning about microservices, containerization, and managing multi-container applications in a cloud environment.

## 🚀 Features

- **Modular Architecture**: Each service is containerized, promoting separation of concerns and easy scaling.
- **Kubernetes Orchestration**: Managed with Kubernetes to automate deployment, scaling, and management of containerized applications.
- **Continuous Integration**: GitHub Actions set up for automated builds and testing.
- **Flexible Configuration**: Uses `docker-compose` for local development and Kubernetes manifests for cloud deployment.

## 🛠 Technologies Used

- **Frontend**: HTML, Django and JavaScript
- **Backend Services**: Python 
- **Database**:  Postgres
- **Reverse Proxy**: NGINX for load balancing and reverse proxying
- **Containerization**: Docker, Docker Compose for development
- **Orchestration**: Kubernetes
- **CI/CD**: GitHub Actions

## 📚 How It Works

1. **Frontend (`client` folder)**:
   - The client is a web application built with HTML, Django and JavaScript.
   - Communicates with backend services to fetch and display data.

2. **Backend (`server` and `worker` folders)**:
   - The `server` acts as the main API provider, serving requests from the frontend.
   - The `worker` performs background tasks (e.g., processing jobs, handling asynchronous tasks).

3. **NGINX**:
   - Acts as a reverse proxy to route traffic to the appropriate service.
   - Balances load between multiple instances of services if needed.

4. **Kubernetes (`k8s` folder)**:
   - Contains deployment and service manifests for Kubernetes.
   - Handles scaling, monitoring, and managing the lifecycle of containers.

5. **GitHub Actions**:
   - Provides CI/CD functionality to automate testing and building of the Docker images.





