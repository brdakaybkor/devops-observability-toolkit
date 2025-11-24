# DevOps Observability Toolkit
A complete end-to-end observability stack integrating **Prometheus, Grafana, Loki, Alertmanager, Node Exporter, MySQL Exporter, Redis Exporter, and JVM Metrics**.  
This toolkit demonstrates how to build a **production-grade monitoring system** similar to what I deployed at Tamam Finance.

---

## 🚀 Features
- Full metrics collection for microservices, databases, servers, and containers  
- Centralized log aggregation using Loki  
- Alerting with email/SMS/Webhook  
- Ready-made Grafana dashboards for:
  - Java/Spring Boot services
  - Kubernetes clusters
  - MySQL & Redis performance
  - API latency & throughput
- Docker Compose orchestration  
- Extensible for Kubernetes & cloud-native environments  

---

## 📦 Stack Components
| Component | Purpose |
|----------|---------|
| Prometheus | Metrics scraping & storage |
| Grafana | Dashboards & visualization |
| Loki | Log aggregation |
| Alertmanager | Alerts & notifications |
| Node Exporter | OS-level metrics |
| MySQL/Redis Exporters | Database monitoring |
| JVM Exporter | Java app metrics |

---

## 📁 Project Structure

devops-observability-toolkit/
├── docker-compose.yml
├── prometheus/
│ ├── prometheus.yml
│ └── alert.rules.yml
├── grafana/
│ ├── dashboards/
│ └── provisioning/
├── loki/
│ └── config.yml
└── exporters/


---

## ▶️ Getting Started
```bash
git clone https://github.com/brdakaybkor/devops-observability-toolkit
cd devops-observability-toolkit
docker-compose up -d


Prometheus: http://localhost:9090

Grafana: http://localhost:3000

## 📊 Dashboard Samples

Java Microservice Metrics

Kubernetes Node Health

API Performance Overview

Database Query Latency
