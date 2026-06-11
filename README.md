# 🚀 ISH Habit Tracker

A modern and responsive Habit Tracker web application designed to help users build consistency, track daily habits, and visualize progress through interactive analytics.

The project was developed as a frontend application and later containerized using Docker, published to Docker Hub, and deployed on AWS EC2 using Nginx.

---

# 🌐 Live Demo

**GitHub Pages:**

https://yashtrivedi0402.github.io/HABIT-TRACKER/

---

# ✨ Features

* Create and manage daily habits
* Track daily progress and completion status
* Interactive analytics dashboard
* Modern Glassmorphism user interface
* Fully responsive design
* Local Storage based persistence
* Real-time charts powered by Chart.js
* Dockerized deployment support
* Cloud deployment ready

---

# 🛠️ Tech Stack

## Frontend

* HTML5
* CSS3
* JavaScript (ES6)
* Chart.js

## DevOps & Cloud

* Git
* GitHub
* GitHub Pages
* Docker
* Docker Hub
* Nginx
* AWS EC2
* Ubuntu 22.04 LTS

---

# 📸 Screenshots

<img width="1830" height="845" alt="Screenshot 2026-06-07 025113" src="https://github.com/user-attachments/assets/efb970e2-91bd-44fd-9158-1259a71c64d6" />

<img width="1839" height="859" alt="Screenshot 2026-06-07 025126" src="https://github.com/user-attachments/assets/6abe2f06-1552-4f64-8325-71e8d15ddf91" />

<img width="1857" height="847" alt="Screenshot 2026-06-07 025139" src="https://github.com/user-attachments/assets/d0adf040-7e6e-44d0-9131-3c9016089bd0" />

<img width="1836" height="863" alt="Screenshot 2026-06-07 025148" src="https://github.com/user-attachments/assets/50e154d5-85b9-402a-a412-fc645df54257" />

<img width="1449" height="91" alt="Screenshot 2026-06-07 120229" src="https://github.com/user-attachments/assets/c74d513a-7fb7-4f3c-b079-11a5a5d33686" />

<img width="1880" height="853" alt="Screenshot 2026-06-07 120247" src="https://github.com/user-attachments/assets/ce442bc0-4e41-40bc-8f54-f7a66b7c9fea" />

<img width="1705" height="909" alt="Screenshot 2026-06-07 120325" src="https://github.com/user-attachments/assets/1156a788-73ef-4be6-9b39-b5d80db7c8d6" />


---

# 🐳 Containerization & Deployment

This application has been containerized using Docker and served through Nginx to ensure portability and consistent deployment across environments.

## Build Docker Image

```bash
docker build -t habit-tracker .
```

## Run Locally

```bash
docker run -d -p 8081:80 --name habit-app habit-tracker
```

Access:

```text
http://localhost:8081
```

---

# 📦 Docker Hub

Pre-built Docker image is available on Docker Hub.

Pull Image:

```bash
docker pull yashtri0204/habit-tracker:v1
```

Run Image:

```bash
docker run -d -p 8081:80 yashtri0204/habit-tracker:v1
```

Docker Hub Repository:

https://hub.docker.com/r/yashtri0204/habit-tracker

---

# ☁️ AWS EC2 Deployment

The application has been successfully deployed on an Ubuntu-based AWS EC2 instance.

## Deployment Process

```text
GitHub Repository
        ↓
Docker Build
        ↓
Docker Hub
        ↓
AWS EC2
        ↓
Docker Container
        ↓
Running Application
```

## Commands Used

Install Docker:

```bash
sudo apt update
sudo apt install docker.io -y
```

Pull Docker Image:

```bash
docker pull yashtri0204/habit-tracker:v1
```

Run Container:

```bash
docker run -d -p 80:80 --name habit-app yashtri0204/habit-tracker:v1
```

Verify Running Containers:

```bash
docker ps
```

---

# 📂 Project Structure

```text
HABIT-TRACKER/
│
├── index.html
├── Dockerfile
├── README.md

```

## Key Files

| File         | Purpose                         |
| ------------ | ------------------------------- |
| index.html   | Main application logic and UI   |
| Dockerfile   | Docker image build instructions |
| README.md    | Project documentation           |
---

# 🎯 Learning Outcomes

Through this project, I gained hands-on experience with:

* Git and GitHub workflow
* Docker image creation
* Docker container lifecycle management
* Docker Hub image publishing
* Linux server administration
* AWS EC2 deployment
* Nginx web serving
* Cloud-based application deployment

---

# 🔮 Future Enhancements

# 🔮 Future Enhancements

## Phase 1: CI/CD Automation (Next Priority)

* GitHub Actions CI Pipeline
* Automatic Docker Image Build
* Automatic Docker Hub Push
* Build Status Badge in README

## Phase 2: Production Deployment

* Automatic EC2 Deployment
* Zero-Downtime Deployment Strategy
* Environment Variable Management
* Production Configuration Management

## Phase 3: Monitoring & Observability

* Prometheus Integration
* Grafana Dashboards
* Container Health Monitoring
* Resource Usage Metrics

## Phase 4: Container Orchestration

* Docker Compose Setup
* Multi-Container Architecture
* Kubernetes Deployment
* Kubernetes Service & Ingress Configuration

## Phase 5: Infrastructure as Code

* Terraform for AWS Infrastructure
* Automated EC2 Provisioning
* Security Group Automation
* Reproducible Infrastructure

## Phase 6: Production Readiness

* Custom Domain Configuration
* HTTPS using Let's Encrypt
* Reverse Proxy Configuration
* Log Aggregation & Monitoring

```
```


# 👨‍💻 Author

**Yash Trivedi**

GitHub:
https://github.com/yashtrivedi0402
