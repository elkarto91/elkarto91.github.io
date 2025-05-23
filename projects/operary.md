---
title: "Operary"
description: "The coordination engine for modern industrial operations. API-first, audit-ready, and built for shift-based execution."
date: 2024-05-23
repo: https://github.com/elkarto91/operary
status: "v0.1.0 – MVP Released"
tags: ["go", "api", "mongodb", "supplychain", "audit", "iot"]
---

<img src="/assets/operary/operary-banner.png" alt="Operary banner" style="width: 100%; margin-bottom: 2rem;" />

## 🛰️ What is Operary?

**Operary** is a coordination layer for frontline industrial teams. It allows machines, humans, and systems to work together with:

- 🧠 Task orchestration from signals or humans  
- 🕓 Shift lifecycle management  
- 🔐 Token-secured APIs  
- 🧾 Automatic audit logging  
- 📈 Uptime and trace metrics  
- 🛎️ Background event notifier service

---

## 🧪 Features

| Module | What It Does |
|--------|--------------|
| ✅ Tasks API | Create, assign, and complete operational tasks  
| ✅ Shift API | Start and close shift blocks  
| ✅ Audit Log | Traceable, immutable record of all events  
| ✅ Org Token Auth | Secured by API header  
| ✅ Metrics Endpoint | Prometheus-ready uptime + request count  
| ✅ Postman & Simulation | Test collections and sample runs  
| ✅ Docker Compose | Runs with MongoDB locally or on cloud  

---

## 📦 Tech Stack

- 🧬 Go (chi router)  
- 🧰 MongoDB  
- 🔐 Zap logger + Org token middleware  
- 📜 OpenAPI spec  
- 🐳 Docker, Makefile, run.sh

---

## 🚀 Try It Out

```bash
git clone https://github.com/elkarto91/operary
cd backend
docker-compose up --build
Then test the endpoints at **http://localhost:8080/v1** or use the **Postman Collection**.

---

## 🧠 System Signal Value

**Operary** is part of the **System Signal Five**—a portfolio of intelligent, trust-layered enterprise coordination systems.

🔗 [Explore more projects](https://systemsignal.dev/projects)

---

## 📸 Screenshots

* Wireframe
* System Diagram
* Audit Log UI (simulated)

---

## 📥 Resources

* [GitHub Repository](https://github.com/elkarto91/operary) * [OpenAPI Spec](https://github.com/elkarto91/operary/tree/main/api_spec) * [Postman Collection](https://your-postman-collection-link) * [Launch Blog Post](https://your-blog-post-link) “Coordination should be observable. Operary is where signals meet trust.”