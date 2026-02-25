# Distributed Services in Go

This project is a hands-on journey to build production-style distributed services in Go. The goal is to explore how modern backend systems are designed, implemented, observed, and deployed using a contract-first approach with Protobuf and gRPC.

## What this project will cover

- **Protobuf-first API design**: define service contracts and message schemas, evolve them safely, and generate Go code from `.proto` files.
- **gRPC communication**: implement strongly typed RPC APIs and understand request/response flows, streaming basics, and error handling patterns.
- **Server-side services**: build modular Go gRPC servers with clear boundaries between transport, business logic, and storage layers.
- **Client-side services**: create resilient gRPC clients with connection management, retries, timeouts, and interceptors.
- **Observability**: add structured logging, metrics, and tracing so service behavior can be monitored and debugged in real environments.
- **Deployment**: package services for reproducible environments and automate local and cloud-ready deployment workflows.
- **Kubernetes**: run services on Kubernetes, manage configuration and scaling, and apply practical patterns for health checks and reliability.

## Objective

By the end of this project, I aim to have a complete Go-based microservices foundation that demonstrates end-to-end development: from API contracts to running distributed services in Kubernetes with solid observability and deployment practices.
