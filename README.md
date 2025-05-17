
# DevOps Capstone Project 🏁

This capstone project represents the final milestone of the **IBM DevOps and Software Engineering Professional Certificate**. It integrates everything learned throughout the program into a full-stack, production-grade microservice.

## 🚀 Overview
In this project, I built and deployed a microservice with:
- Flask RESTful API
- PostgreSQL database (via Docker)
- Test coverage ≥ 95% using TDD
- CI/CD pipeline
- Kubernetes-ready configuration

## 🧰 Tech Stack
- Python 3.9
- Flask
- PostgreSQL
- Docker
- GitHub Actions
- Kubernetes (K3D local setup)
- Pytest, FactoryBoy

## 📁 Folder Structure
```
├── service/
│ ├── config.py
│ ├── models.py
│ ├── routes.py
│ └── common/
├── tests/
│ ├── factories.py
│ ├── test_models.py
│ └── test_routes.py
├── bin/setup.sh
├── Dockerfile
├── Makefile
```

## 🧪 Run Tests
```
make test
```
## 🐳 Docker Usage
Build and run the app
```
make build
make run
```
Start PostgreSQL container
```
make db
```
## ☸️ Kubernetes Support
Includes scripts to set up Tekton tasks and simulate IBM Cloud IDE locally via:
```
make cluster
make tekton
make clustertasks
```
## 📄 License
Apache 2.0

## Author
[John Rofrano](https://www.coursera.org/instructor/johnrofrano), Senior Technical Staff Member, DevOps Champion, @ IBM Research, and Instructor @ Coursera
