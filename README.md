# 🚀 DevOps CI/CD Java Project

This project demonstrates a **complete CI/CD pipeline** for a Java Spring Boot app using **GitHub Actions** and **Docker**.

## 🧱 Features
- Build & test Java application with Maven
- Build Docker image
- Run container and verify HTTP response
- Publish build artifact automatically

## 🧰 Tools
- Java 17 / Spring Boot 3
- Maven
- Docker
- GitHub Actions

## 🏃‍♂️ Run locally
```bash
docker build -t demo-app .
docker run -p 8080:8080 demo-app
```
Then open http://localhost:8080 🚀
