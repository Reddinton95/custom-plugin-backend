---
name: performance-optimization
description: Optimize application performance through caching strategies, load balancing, database scaling, and monitoring. Build systems handling thousands of concurrent users.
---

# Performance Optimization

This skill teaches building and maintaining high-performance systems.

## Quick Start

Performance optimization involves:
- **Caching**: Reduce database load
- **Scaling**: Handle more users
- **Monitoring**: Measure and improve
- **Profiling**: Find bottlenecks

## Key Concepts

### Caching Strategies
- Cache-aside: Application fetches from DB then caches
- Write-through: Write goes through cache to DB
- Write-behind: Async write to DB
- Refresh-ahead: Proactive refresh before expiration

### Scaling
- **Horizontal**: Add more servers with load balancing
- **Vertical**: Add more resources to single server
- **Database**: Read replicas, sharding, federation

### Load Balancing
- Round-robin
- Least connections
- Consistent hashing (for distributed systems)
- Health-based routing

### Monitoring
- Application Performance Monitoring (APM)
- Distributed tracing
- Metrics and dashboards
- Alerting and on-call

## Tools & Technologies

- **Caching**: Redis, Memcached
- **APM**: Datadog, New Relic, Elastic
- **Tracing**: Jaeger, Zipkin, OpenTelemetry
- **Load Balancers**: Nginx, HAProxy, Cloud LB

## Hands-On Projects

- Implement caching
- Set up load balancing
- Database sharding
- Performance profiling
- APM integration

## See Also
- Agent 5: Caching & Performance (8-week guide)
- Redis and Memcached documentation
- System Design Primer for scaling patterns
