# 🚀 ISH Habit Tracker

A modern and responsive Habit Tracker web application designed to help users build consistency, track daily habits, and visualize progress through interactive analytics.

## 🌐 Live Demo

https://yashtrivedi0402.github.io/HABIT-TRACKER/

---

## ✨ Features

* Create and manage daily habits
* Track habit completion status
* Interactive analytics dashboard
* Beautiful Glassmorphism UI
* Responsive design for desktop and mobile
* Local Storage support for persistent data
* Real-time progress visualization using Chart.js

---

## 🛠️ Tech Stack

### Frontend

* HTML5
* CSS3
* JavaScript (ES6)
* Chart.js

### DevOps

* Git
* GitHub
* Docker
* Nginx

---

## 📸 Screenshots

### Dashboard Overview

<img width="1830" height="845" alt="Screenshot 2026-06-07 025113" src="https://github.com/user-attachments/assets/efb970e2-91bd-44fd-9158-1259a71c64d6" />

<img width="1839" height="859" alt="Screenshot 2026-06-07 025126" src="https://github.com/user-attachments/assets/6abe2f06-1552-4f64-8325-71e8d15ddf91" />

<img width="1857" height="847" alt="Screenshot 2026-06-07 025139" src="https://github.com/user-attachments/assets/d0adf040-7e6e-44d0-9131-3c9016089bd0" />

<img width="1836" height="863" alt="Screenshot 2026-06-07 025148" src="https://github.com/user-attachments/assets/50e154d5-85b9-402a-a412-fc645df54257" />

<img width="1449" height="91" alt="Screenshot 2026-06-07 120229" src="https://github.com/user-attachments/assets/c74d513a-7fb7-4f3c-b079-11a5a5d33686" />

<img width="1880" height="853" alt="Screenshot 2026-06-07 120247" src="https://github.com/user-attachments/assets/ce442bc0-4e41-40bc-8f54-f7a66b7c9fea" />

<img width="1705" height="909" alt="Screenshot 2026-06-07 120325" src="https://github.com/user-attachments/assets/1156a788-73ef-4be6-9b39-b5d80db7c8d6" />

## 🐳 Containerization & Deployment

This application has been containerized using Docker and served through Nginx for consistent deployment across environments.

### Build Docker Image

```bash
docker build -t habit-tracker .
```

### Run Locally

```bash
docker run -d -p 8081:80 --name habit-app habit-tracker
```

Access the application:

```text
http://localhost:8081
```

### Docker Hub

Pull the pre-built image directly from Docker Hub:

```bash
docker pull yashtri0204/habit-tracker:v1
```

Run the Docker Hub image:

```bash
docker run -d -p 8081:80 yashtri0204/habit-tracker:v1
```

### Deployment Workflow

```text
Source Code
     ↓
GitHub Repository
     ↓
Docker Build
     ↓
Docker Hub Registry
     ↓
Docker Container
     ↓
Running Application
```

---

## 📂 Project Structure

```text
HABIT-TRACKER/
│
├── index.html
├── Dockerfile
├── README.md
```

### Key Files

| File         | Purpose                      |
| ------------ | ---------------------------- |
| index.html   | Main application             |
| Dockerfile   | Container build instructions |
| README.md    | Project documentation        |

```
```


## 🔮 Future Enhancements

* User Authentication
* Cloud Database Integration
* Habit Streak Tracking
* Reminder Notifications
* AWS Deployment
* GitHub Actions CI/CD Pipeline
* Monitoring with Prometheus & Grafana

---

## 👨‍💻 Author

Yash Trivedi

GitHub:
https://github.com/yashtrivedi0402
