# Multi-Database Docker Compose Stack

This project shows how to run PostgreSQL, MariaDB, and MongoDB together using Docker Compose on Chromebook Linux.

## 🚀 Setup
1. Clone the repository:
   git clone https://github.com/ArghadeepRathore/docker-multi-db-stack.git
   cd docker-multi-db-stack

2. Start the stack:
   sudo docker-compose up -d

3. Check containers:
   sudo docker ps

## 🔧 Usage
- PostgreSQL: psql -h localhost -p 5433 -U arghadeep -d postgres
- MariaDB: mysql -h localhost -P 3307 -u root -p
- MongoDB: mongosh --host localhost --port 27017

## 🛠 Tech Stack
- Docker & Docker Compose
- PostgreSQL 15
- MariaDB 11
- MongoDB 4.4

## 🌟 Portfolio Value
This project proves you can:
- Orchestrate multiple databases in Docker
- Solve port conflicts and container issues
- Build a backend environment ready for real apps

