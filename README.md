# 🚀 Docker Multi-Service Deployment using Docker Compose

A simple multi-container Docker Compose project that demonstrates how to deploy multiple services including an Nginx web server, a Java application, and a Maven build container.

---

# 📖 Project Overview

This project demonstrates deploying multiple Docker containers using **Docker Compose**.

The project contains:

- 🌐 Nginx Web Server
- ☕ Java Application
- 📦 Maven Build Container

---

# 🎯 Project Objectives

- Learn Docker Images
- Learn Docker Containers
- Build Custom Docker Images
- Deploy Multiple Containers
- Understand Docker Compose
- Expose Services using Ports

---

# 🛠 Technologies Used

| Technology | Purpose |
|------------|---------|
| Docker | Containerization |
| Docker Compose | Multi-container Deployment |
| Java | Sample Application |
| Maven | Build Tool |
| HTML | Static Website |
| Linux | Development Environment |

---

# 📁 Project Structure

```text
docker-multi-service-deployment/
│
├── docker-compose.yml
├── README.md
│
├── java-app/
│   ├── Dockerfile
│   └── Hello.java
│
├── maven-app/
│   ├── Dockerfile
│   ├── pom.xml
│   └── src/
│       └── main/
│           └── java/
│               └── App.java
│
├── web-host/
│   ├── Dockerfile
│   └── index.html
│
└── screenshots/
    ├── docker-compose-up.png.jpeg
    ├── docker-ps.png.jpeg
    └── website.png.jpeg
```

---

# 🏗 Architecture

```text
                 Docker Compose
                        │
        ┌───────────────┼───────────────┐
        │               │               │
      Nginx          Java App       Maven Build
        │               │               │
        └───────────────┼───────────────┘
                        │
                 Docker Network
```

---

# 🚀 Getting Started

## Clone Repository

```bash
git clone https://github.com/Siva5752/docker-multi-service-deployment.git
```

## Go to Project Folder

```bash
cd docker-multi-service-deployment
```

## Build Images

```bash
docker compose build
```

## Start Containers

```bash
docker compose up
```

or

```bash
docker compose up --build
```

## View Running Containers

```bash
docker ps
```

## Stop Containers

```bash
docker compose down
```

---

# 📸 Project Screenshots

## Docker Compose Execution

![Docker Compose](screenshots/docker-compose-up.png.jpeg)

Docker Compose starting all services.

---

## Running Containers

![Docker Containers](screenshots/docker-ps.png.jpeg)

Shows the running Nginx container.

---

## Static Website

![Website](screenshots/website.png.jpeg)

Website hosted successfully using the Nginx container.

---

# 📚 Docker Compose Commands

| Command | Description |
|----------|-------------|
| docker compose build | Build Docker Images |
| docker compose up | Start Containers |
| docker compose up --build | Build & Start |
| docker compose down | Stop Containers |
| docker ps | Running Containers |
| docker ps -a | All Containers |

---

# 📖 Docker Concepts Used

### Docker Images

Created custom Docker images using Dockerfiles.

### Docker Containers

Ran multiple containers together.

### Docker Compose

Managed all services using a single YAML file.

### Port Mapping

Mapped port **8080 → 80**.

### Bridge Network

Containers communicate through Docker's default bridge network.

---

# 💡 What I Learned

- Docker Images
- Docker Containers
- Dockerfile
- Docker Compose
- Docker Networking
- Port Mapping
- Multi-container Deployment
- Building Custom Images

---

# 🚀 Future Improvements

- Add MySQL Database
- Add Spring Boot Application
- Add Jenkins CI/CD
- Add Kubernetes Deployment
- Add Monitoring using Prometheus & Grafana

---

# 👨‍💻 Author

**Siva**

DevOps Engineer

GitHub: https://github.com/Siva5752

---

Thank you for visiting this repository! 🚀

