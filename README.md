# SetCore

Welcome to the official GitHub organization for **SetCore** — a production-grade ecosystem of high-performance, modular infrastructure components, developer tooling, and autonomous operation utilities designed for resilient distributed systems.

Our philosophy is built around strict design constraints: absolute subsystem isolation, compile-time contract enforcement, minimal allocations, and high-throughput data processing.

## The SetCore Ecosystem

### 🧠 Operations & AIOps
* **[telemair](https://github.com)**: The Autonomous OpenSource AIOps & Remediation Platform. Ingests high-throughput OTLP streams, correlates complex incidents, and leverages a secure agent to generate valid, sandboxed Draft Merge Requests to fix production code exceptions.

### 🌐 Networking & Data Plane
* **[gateway](https://github.com)**: High-performance, cloud-native API Gateway orchestrated for modern microservices. Built on ConnectRPC/gRPC protocols, features ultra-low latency routing, native idempotency enforcement, and dynamic OpenTelemetry instrumentation out of the box.

### 📊 Storage & Lifecycle
* **[migrator](https://github.com)**: Highly reliable database schema migration utility engine engineered for cloud-native state stores (ClickHouse, PostgreSQL, SQLite). Supports embedded migrations, topological dependency routing, and seamless zero-downtime integration hooks for distributed systems.

## Core Engineering Principles
Across all SetCore projects, we strictly enforce:
1. **Zero Cross-Cutting Compile-Time Dependencies:** Every project enforces clean modular boundaries to eliminate structural technical debt.
2. **Extreme Performance & Resource Efficiency:** Hot paths are optimized for high-throughput and predictable memory utilization using modern Go patterns.
3. **Open Standards First:** Native alignment with CNCF paradigms — OpenTelemetry (OTel), OpAMP, CloudEvents, and Model Context Protocol (MCP).

---
🌐 [Website](https://setcore.io) · 🛡️ [Security Policy](./SECURITY.md)
