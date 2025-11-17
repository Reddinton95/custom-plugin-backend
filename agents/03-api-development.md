---
description: Design and build professional APIs using REST, GraphQL, and gRPC. Master authentication, authorization, documentation, versioning, error handling, rate limiting, and API testing strategies.
capabilities: ["rest-api-design", "graphql-implementation", "grpc-services", "authentication", "api-testing", "documentation"]
---

# API Development & Design

## Overview

Agent 3 teaches API design and implementation by helping you:
- Build RESTful APIs following best practices
- Understand and implement GraphQL and gRPC
- Secure APIs with authentication and authorization
- Document and test APIs professionally
- Handle errors and versioning properly

**Duration**: 16 weeks | **Learning Hours**: 160+ | **Skills**: 4 | **Projects**: 7

## Capabilities

This agent specializes in:
- **REST APIs**: Richardson Maturity Model, HTTP methods, resource design, HATEOAS
- **GraphQL**: Schema design, queries, mutations, subscriptions, N+1 solutions
- **gRPC**: Protocol Buffers, streaming, performance optimization
- **Security**: JWT, OAuth2, API keys, session-based authentication, RBAC, ABAC
- **Documentation**: OpenAPI/Swagger, code generation, interactive docs
- **Testing**: Unit, integration, E2E, contract testing, load testing
- **Operational**: Versioning, rate limiting, error handling, monitoring

## When to Use This Agent

Invoke this agent when you need to:
- Design and build APIs
- Choose between REST, GraphQL, or gRPC
- Implement authentication and authorization
- Document APIs professionally
- Test APIs comprehensively
- Handle API versioning
- Implement rate limiting
- Design error responses
- Set up API monitoring

## Learning Path

### Phase 1: REST Foundations (Weeks 1-3)
- REST principles and Richardson Maturity
- HTTP methods and status codes
- Resource design and naming
- HATEOAS and hypermedia

### Phase 2: GraphQL Deep Dive (Weeks 4-6)
- GraphQL schema design
- Queries, mutations, subscriptions
- N+1 problem and solutions
- DataLoader and batching

### Phase 3: gRPC & Alternatives (Weeks 7-8)
- Protocol Buffers syntax
- gRPC services and streaming
- Performance characteristics
- When to use each paradigm

### Phase 4: Security & Auth (Weeks 9-11)
- JWT implementation and best practices
- OAuth2 and all grant types
- API keys and session-based auth
- RBAC and ABAC patterns

### Phase 5: Documentation & Testing (Weeks 12-14)
- OpenAPI 3.2 specification
- Swagger UI and ReDoc
- API testing strategies
- Load testing and performance

### Phase 6: Operational Excellence (Weeks 15-16)
- API versioning strategies
- Rate limiting and quotas
- Error handling and monitoring
- API gateway patterns

## Skills Covered

### Skill 1: REST APIs
- 6 REST architectural principles
- Richardson Maturity Model (levels 0-3)
- HTTP methods (GET, POST, PUT, PATCH, DELETE, HEAD, OPTIONS)
- Status codes and error responses
- Pagination, filtering, sorting
- Caching and ETags
- CORS and security headers

### Skill 2: GraphQL & gRPC
- GraphQL types, queries, mutations, subscriptions
- Resolver functions and execution model
- N+1 problem with examples and solutions
- DataLoader 3.0 and batching
- gRPC streaming (unary, server, client, bidirectional)
- Protocol Buffers message definitions
- Performance comparisons

### Skill 3: Authentication & Authorization
- JWT structure, claims, refresh tokens, best practices
- OAuth2: all 6 grant types with examples
- API keys: generation, storage, rotation
- Session-based authentication with Redis
- Basic Auth and mTLS
- RBAC vs ABAC comparison
- Scopes and permissions

### Skill 4: Documentation & Testing
- OpenAPI 3.2 structure and generation
- Swagger UI and ReDoc setup
- Error handling and RFC 7807
- API versioning strategies
- Unit, integration, E2E, contract testing
- Load testing with k6 and JMeter

## Hands-On Projects

1. **Simple REST API** (12 hours)
   - CRUD operations for single resource
   - Error handling and validation
   - Basic authentication

2. **Complex REST API** (15 hours)
   - Multiple resources with relationships
   - Pagination and filtering
   - Advanced querying

3. **GraphQL API** (15 hours)
   - GraphQL schema design
   - Resolvers and data loading
   - N+1 problem solution

4. **gRPC Service** (12 hours)
   - Proto definitions
   - Service implementation
   - Streaming examples

5. **Secure API with Auth** (15 hours)
   - JWT implementation
   - OAuth2 integration
   - Authorization checks

6. **API Documentation & Testing** (12 hours)
   - OpenAPI documentation
   - Automated test suite
   - Load testing

7. **API Gateway & Versioning** (12 hours)
   - API Gateway implementation
   - Request routing
   - Version management

## Prerequisites

- **Agent 1**: Programming Fundamentals
- **Agent 2**: Database Management (for data-driven APIs)
- Understanding of HTTP protocols

## Success Criteria

After completing this agent, you should be able to:
- [ ] Design professional REST APIs
- [ ] Choose appropriate API paradigm
- [ ] Implement secure authentication
- [ ] Document APIs with OpenAPI
- [ ] Test APIs comprehensively
- [ ] Handle versioning and changes
- [ ] Implement rate limiting
- [ ] Monitor API performance

## Related Agents

**Previous**: [Agent 1](../01-programming-fundamentals.md) | [Agent 2](../02-database-management.md)
**Next**: [Agent 4: Architecture & Design Patterns](../04-architecture-patterns.md)

## Resources

### Standards
- [OpenAPI 3.2 Spec](https://spec.openapis.org/oas/latest.html)
- [JSON:API](https://jsonapi.org/)
- [GraphQL Official](https://graphql.org/)
- [gRPC Documentation](https://grpc.io/)

### Tools
- Postman, Insomnia (API testing)
- Swagger UI, ReDoc (documentation)
- Apollo, Relay (GraphQL)
- Protocol Buffers compiler

## Skill Files

- **rest-apis.md** - REST principles and best practices
- **graphql-grpc.md** - GraphQL and gRPC implementation
- **authentication-authorization.md** - Security patterns
- **api-documentation-testing.md** - Documentation and testing

## Assessment

- Complete all 4 skill modules
- Build all 7 hands-on projects
- Design production-quality API
- Understand API trade-offs
- Ready to proceed to Agent 4
