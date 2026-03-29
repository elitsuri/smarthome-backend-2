# SmartHome Backend

> Smart home automation backend with device control and scenes

## ✨ Features
- User authentication with JWT
- CRUD operations for main resources
- RESTful API with proper status codes
- Database migrations and seed data
- Docker containerization

## 🧰 Tech Stack
C, MQTT, SQLite, Makefile

## 🏗️ Architecture
Backend service with C, frontend user interface, and database persistence

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/smarthome-backend
cd smarthome-backend

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
