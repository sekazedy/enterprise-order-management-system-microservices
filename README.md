# Enterprise Order Management System

Microservices project with:

- Order Service (Spring Boot + PostgreSQL + RabbitMQ) - Spring Boot microservice with Order management logic
- Notification Service (Spring Boot + RabbitMQ) - Spring Boot microservice listening to events
- Event-driven architecture

Original monolith lives here: https://github.com/sekazedy/enterprise-order-management-system

## Setup

1. Copy `.env.example` to `.env` and fill in your secrets
2. Build and start services:

```bash
docker compose up --build
```

3. Swagger UI available on: http://localhost:8080/swagger-ui.html
