# Checkout Survival Kit for Newcomers

- TOC
{:toc}

## Functionality
### Position in the E2E e-commerce process
### Checkout core business process (Cart to Order)
### Checkout sources
- Cart
- Draft order
- Buy button
- POS
### Checkout targets
- Order

## Architecture
### Overall architecture
- Core entities
- Use cases
- Controllers, Gateways, Presenters
- Web, UI, Database, External interfaces, Devices
### Backend
- Core entites
- Use cases
- Controllers, Gateways, Presenters
### Web Server
- Controllers, Gateways, Presenters
### GraphQL
- Controllers, Gateways, Presenters
### Frontend
- Web 
- Devices (POS)
### Persistence
- Database
### Middleware
- Job queue (Resque)
- In memory cache (Redis)
- In memory cache (Memcache)
- Message queue (Kafka)
### Integration with other domains
- Cart
- Payment
- Order

## Deployment
### Infrastructure - make abstraction concrete
### Life of a request in checkout 
### Scalability

## Core use cases
### Overview
### Checkout (Cart to Order)
### Offsite payment
### Abandoned checkout

## Error handling
- Violation
- Exception

## Features
- Discount

## Extensibility
- Script

## Checkout classic and checkout one (C1)
### Main difference
### Eligibility for checkout one
### Swtiching between classic and C1
### The migration project
### Impact on merchant and buyer
### Impact on issue solving

## Issue solving guide
### Decision tree
### Tools
- Rails console
- Lint
- Unit test
### Observability
- Logs (Splunk)
- Exceptions (Bugsnag)
- Violations (Datadog)
- Metrics (Grafana)
- Profile (Speedscope)

