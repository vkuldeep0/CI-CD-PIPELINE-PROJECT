# 🧠 Flask System Insight

A containerized Flask app that monitors system metrics (CPU, RAM, Disk), stores them in SQLite, and displays them via a live dashboard.

## 🔧 Features
- Real-time system monitoring
- Flask + APScheduler + SQLite
- Chart.js dashboard
- Dockerized app
- Healthcheck endpoint
- CI/CD pipeline with GitHub Actions

## 🐳 Run Locally
```bash
docker build -t flask-system-insight .
docker run -p 5000:5000 flask-system-insight
```
Then open: http://localhost:5000/
