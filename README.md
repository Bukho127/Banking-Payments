# Banking-Payments
Modern banking backend in Go, built with DDD, TDD,  Microservice and clean architecture


This was inspired by the book that I picked up on the internet "Engneering South the south african banks". I ask myself how can I make the banking more scalable and also cheaper to build. # Banking-Payments

A modern banking backend in Go, built with Domain-Driven Design (DDD), Test-Driven Development (TDD), microservices, and clean architecture.

## Motivation

This project was inspired by *Engineering the South African bank*. It made me ask: **how can banking systems be made more scalable and cheaper to build?**

This repository is my attempt to answer that by combining:

- **Small, independently deployable services**, so each can scale on its own
- **Clean architecture**, so business rules don't depend on frameworks or databases
- **Strong automated testing (TDD)**, so changes are safe and cheap to make
- **Open-source infrastructure** (PostgreSQL, Redis, NATS) instead of expensive proprietary systems

## Tech Stack

Go, PostgreSQL, Redis, NATS, Docker Compose

## Getting Started

```bash
docker compose up -d
go run ./cmd/wallet
curl localhost:8080/healthz
```

## Project Status

Early development. The first service is the wallet service.
