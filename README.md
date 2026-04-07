# Enterprise Order Management System

Microservices project with:

- Order Service (Spring Boot + PostgreSQL + RabbitMQ)
- Notification Service (Spring Boot + RabbitMQ)
- Event-driven architecture

## Setup

1. Copy `.env.example` to `.env` and fill in your secrets
2. Build and start services:

```bash
docker compose up --build
```

3. Swagger UI available on: http://localhost:8080/swagger-ui.html
