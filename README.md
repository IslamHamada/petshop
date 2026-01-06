# PetShop -- Microservices E-Commerce Platform

PetShop is a fully containerized microservices-based e-commerce
application built with **Spring Boot**, **Angular**, **Auth0**,
**Docker**, **Kubernetes**, and **Jenkins CI/CD**.\
It also demonstrates:
- Centralizaed configuration (Spring Cloud Config)
- Service discovery (Eureka)
- API Gateway routing
- JWT auth (Auth0)
- Distributed tracing to ZipKin + log correlation (traceId/spanId)

### Frontend / Gateway:
- https://34.54.201.1.sslip.io/ (temporarily down!)

## 🧩 Microservices & Repositories

### Business Services

-   **Product Service**\
    https://github.com/IslamHamada/petshop_productservice
-   **Cart Service**\
    https://github.com/IslamHamada/petshop_cartservice
-   **Order Service**\
    https://github.com/IslamHamada/petshop_orderservice
-   **User Service**\
    https://github.com/IslamHamada/petshop_userservice

### Infrastructure

-   **API Gateway**\
    https://github.com/IslamHamada/petshop_gateway
-   **Config Server**\
    https://github.com/IslamHamada/petshop_configserver
-   **Service Registry**\
    https://github.com/IslamHamada/petshop_serviceregistry

### Shared

-   **Shared Contracts**\
    https://github.com/IslamHamada/petshop_contracts
-   **Shared Config**\
    https://github.com/IslamHamada/petshop_sharedconfig

### Frontend

-   **Angular UI**\
    https://github.com/IslamHamada/petshop-ui

### Deployment

-   **Deployment Repository (docker‑compose + K8s + MySQL + Zipkin)**\
    https://github.com/IslamHamada/petshop_deployment

## API entry points (via Gateway)
- Product: /product/**
- Cart: /cart/**
- Order: /order/**
- User: /user/**

## Observability
- Traces show up in Zipkin
- Logs include traceId + spanId so you can correlate log lines with Zipkin traces.

## 🛠️ Tech Stack

-   Java 17, Spring Boot 3.x, Spring Cloud
-   Angular, Angular Material, Auth0
-   Docker, Jib, Jenkins, Kubernetes, GKE
