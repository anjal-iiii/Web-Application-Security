# OWASP Top 10

The OWASP Top 10 is an awareness document describing major web application
security risks.

## A01 – Broken Access Control

Users can access resources or perform actions outside their permissions.

Prevention:
- Server-side authorization
- Deny by default
- Role-based access control

## A02 – Cryptographic Failures

Sensitive information is not adequately protected through cryptography.

Prevention:
- HTTPS
- Strong encryption
- Secure password hashing

## A03 – Injection

Untrusted input is interpreted as part of a command or query.

Examples:
- SQL Injection
- Command Injection
- XSS

Prevention:
- Input validation
- Parameterized queries
- Output encoding

## A04 – Insecure Design

Security controls are missing at the design level.

Prevention:
- Threat modeling
- Security requirements
- Secure architecture

## A05 – Security Misconfiguration

Incorrect or insecure configuration exposes the application.

Examples:
- Default credentials
- Debug mode enabled
- Unnecessary services

## A06 – Vulnerable and Outdated Components

Old or vulnerable libraries and frameworks are used.

Prevention:
- Update dependencies
- Monitor vulnerabilities
- Remove unused components

## A07 – Identification and Authentication Failures

Weak authentication or session management allows unauthorized access.

Prevention:
- Strong passwords
- MFA
- Secure session management
- Account lockout/rate limiting

## A08 – Software and Data Integrity Failures

The application does not adequately verify software, updates or data integrity.

## A09 – Security Logging and Monitoring Failures

Important security events are not properly logged or monitored.

## A10 – Server-Side Request Forgery (SSRF)

The server is manipulated into making requests to unintended resources.
