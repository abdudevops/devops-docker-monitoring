# 🚀 DevOps Project

A full DevOps project including:
- Frontend (React)
- Backend (Node.js)
- Database (MongoDB)
- Docker & Docker Compose
- Nginx Reverse Proxy
- Monitoring with Prometheus & Grafana

---

## 📦 Technologies Used

- React
- Node.js
- MongoDB
- Docker
- Docker Compose
- Nginx
- Prometheus
- Grafana
- Node Exporter

---

## ⚙️ Project Architecture

User → Nginx → Frontend / Backend → Database

Monitoring:
- Prometheus collects metrics
- Grafana displays dashboards

---

## 🐳 Run the Project

```bash
docker compose up -d --build

---

## Then open:

App: http://localhost:8080
Grafana: http://localhost:3001
Prometheus: http://localhost:9090

---

📊 Monitoring

Prometheus

Collects metrics from:
-Node Exporter (CPU, RAM)
-cAdvisor (Docker containers)

---

Grafana

Visual dashboards
-Dashboard ID used:
-1860 (Node Exporte)

---

🔥 Features

-Full containerized app
-Reverse proxy with Nginx
-Real-time monitoring
-Docker containers metrics
-Clean architecture

---

👨‍💻 Author

-Abdullah Ahmed
