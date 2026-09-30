# OWASP Top 10

The OWASP Top 10 is a widely used awareness document that highlights
important web application security risks.

## 1. Broken Access Control

Occurs when users can access resources or perform actions beyond their
authorized permissions.

### Example
A normal user accessing an administrator-only resource.

### Prevention
- Enforce authorization on the server
- Apply least privilege
- Deny access by default

---

## 2. Cryptographic Failures

Occurs when sensitive data is not properly protected using appropriate
cryptographic mechanisms.

### Example
Sensitive information transmitted without adequate protection.

### Prevention
- Use HTTPS/TLS
- Protect sensitive data
- Use strong and modern cryptographic algorithms

---

## 3. Injection

Occurs when untrusted input is interpreted as part of a command or query.

### Example
SQL injection caused by unsafe database queries.

### Prevention
- Use parameterized queries
- Validate input
- Avoid constructing queries from untrusted input

---

## 4. Insecure Design

Occurs when security requirements and protections are missing at the
design level.

### Example
An application allowing unlimited sensitive operations without
appropriate controls.

### Prevention
- Apply secure design principles
- Perform threat modeling
- Define security requirements early

---

## 5. Security Misconfiguration

Occurs when application, server, framework, or security settings are
incorrectly configured.

### Example
Unnecessary services or debugging features being exposed.

### Prevention
- Use secure configurations
- Disable unnecessary features
- Keep configurations reviewed and updated

---

## 6. Vulnerable and Outdated Components

Occurs when applications use components with known security
vulnerabilities or unsupported versions.

### Example
Using an outdated library with a publicly known vulnerability.

### Prevention
- Maintain an inventory of dependencies
- Update components regularly
- Monitor security advisories

---

## 7. Identification and Authentication Failures

Occurs when authentication or session management is implemented
insecurely.

### Example
Weak authentication controls or insecure session handling.

### Prevention
- Use strong authentication
- Protect sessions
- Implement appropriate account protections

---

## 8. Software and Data Integrity Failures

Occurs when software updates, dependencies, or critical data are
trusted without adequate integrity verification.

### Example
Using an untrusted software package or update.

### Prevention
- Verify software integrity
- Use trusted repositories
- Secure CI/CD pipelines

---

## 9. Security Logging and Monitoring Failures

Occurs when important security events are not adequately logged,
monitored, or investigated.

### Example
Repeated failed login attempts occurring without useful security logs.

### Prevention
- Log important security events
- Monitor suspicious activity
- Protect and review logs

---

## 10. Server-Side Request Forgery (SSRF)

Occurs when a server is manipulated into making requests to unintended
locations.

### Example
An application fetching a user-provided URL without sufficient
validation.

### Prevention
- Validate and restrict destination URLs
- Use network segmentation
- Apply appropriate access controls

---

## Summary

The OWASP Top 10 provides a foundation for understanding common web
application security risks and improving secure development practices.
