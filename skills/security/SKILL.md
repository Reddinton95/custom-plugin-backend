---
name: security-practices
description: Secure backend applications against OWASP threats. Implement authentication, encryption, scanning, compliance, and incident response procedures.
---

# Security Practices

This skill teaches securing and maintaining safe backend systems.

## Quick Start

Security involves:
- **Threat prevention**: Defend against OWASP Top 10
- **Authentication**: Who are you?
- **Authorization**: What can you do?
- **Encryption**: Protect data
- **Scanning**: Find vulnerabilities
- **Compliance**: Meet regulations

## OWASP Top 10

1. **Broken Access Control** - Wrong permissions
2. **Cryptographic Failures** - Weak encryption
3. **Injection** - SQL, NoSQL, command injection
4. **Authentication** - Weak password, session attacks
5. **Software and Data Integrity** - Untrusted updates
6. **Vulnerable Components** - Outdated libraries
7. **Identification and Authentication** - Session management
8. **Data Integrity Failures** - Missing encryption
9. **Access Control** - Missing checks
10. **Server-Side Request Forgery (SSRF)** - Untrusted URLs

## Key Concepts

### Authentication
- Passwords: Hashing (bcrypt, argon2)
- JWT: Stateless tokens
- OAuth2: Delegated auth
- MFA: Multiple factors

### Authorization
- RBAC: Role-based access
- ABAC: Attribute-based access
- API scopes and permissions
- Resource ownership

### Encryption
- **At Rest**: AES-256, database encryption
- **In Transit**: TLS 1.3, HTTPS
- **Key Management**: Vaults, key rotation

### Scanning Tools
- **SAST**: SonarQube, Semgrep (source code)
- **DAST**: Burp Suite, OWASP ZAP (running app)
- **SCA**: Snyk, Dependabot (dependencies)
- **Container**: Trivy, Clair

### Compliance
- **GDPR**: Privacy rights, data protection
- **HIPAA**: Healthcare data protection
- **PCI-DSS**: Payment card security
- **SOC 2**: Trust service criteria

## Hands-On Projects

- Fix security vulnerabilities
- Implement authentication
- Set up scanning tools
- Implement compliance
- Create incident procedures

## See Also
- Agent 7: Testing, Security & Monitoring (12-week guide)
- OWASP Top 10 and Cheat Sheets
- "The Web Application Hacker's Handbook"
