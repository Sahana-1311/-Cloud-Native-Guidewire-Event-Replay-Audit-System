# Cloud-Native Guidewire Event Replay & Audit System

An event-driven microservice for capturing, storing, and replaying enterprise transaction events — designed as an audit layer for insurance platforms.

## Overview
Built during the Guidewire GTL Lab program. Models audit and compliance requirements in financial and insurance systems (Guidewire-style architecture).

## Key Features
- Idempotent REST endpoints: POST /events and GET /replay/:id
- Zero duplicate processing guaranteed during simulated node restarts
- Average replay latency under 80ms in load tests
- Structured JSON logs with event ID, timestamp, payload hash, and replay status
- Full traceability for root-cause identification within seconds of any anomaly

## Tech Stack
Python · REST APIs · SQL · Microservices Architecture

## Architecture
Event Sourcing · CQRS · External Integration Layer · Deterministic Replay Engine
