# Dockerized-Microservices
Directory Structure:
microservices-app/
├── docker-compose.yml
├── frontend/
└── backend/
Key Script:
# docker-compose.yml
version: '3'
services:
  frontend:
    build: ./frontend
    ports:
      - "3000:3000"
  backend:
    build: ./backend
    ports:
      - "5000:5000"
