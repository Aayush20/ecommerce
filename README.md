# 🛍️ E-Commerce Backend Platform (Microservices Architecture)

This project is a production-grade, scalable backend for an e-commerce platform built using Java Spring Boot and microservices architecture.

---

## 🧱 Microservices Included

| Service | Description |
|--------|-------------|
| [Auth Service](./auth-service/README.md) | Handles JWT-based authentication and RBAC with custom AOP security |
| [Product Catalog Service](./prod-cat-service/README.md) | CRUD, caching, search, and Kafka-driven stock updates |
| [Order Service](./order-service/README.md) | Processes order placement, event publishing, and rollback |
| [Payment Service](./payment-service/README.md) | Validates payments and communicates payment status |
| [API Gateway](./api-gateway/README.md) | Central entry point for routing and security |
| [Service Discovery](./service-discovery/README.md) | Eureka server for dynamic microservice registration |

---

## ⚙️ Tech Stack

- Java 17, Spring Boot, Spring Cloud
- Redis, Kafka, Elasticsearch, MySQL
- Docker, JUnit, Testcontainers
- Feign, Eureka, Gateway, AOP

---

## ✨ Key Features

- ✅ JWT + Role-based access control
- ✅ Kafka for asynchronous communication
- ✅ Redis caching for performance (product discovery ~50ms)
- ✅ Elasticsearch-powered full-text search
- ✅ Test coverage >90% across services
- ✅ CI/CD ready design with container support

