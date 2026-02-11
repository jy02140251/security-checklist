# Security Checklist

Web application security checklist.

## Authentication

- [ ] Use strong password hashing (bcrypt, argon2)
- [ ] Implement rate limiting on login
- [ ] Use MFA where possible
- [ ] Secure password reset flow
- [ ] Session timeout after inactivity

## Authorization

- [ ] Principle of least privilege
- [ ] Validate permissions on every request
- [ ] Use RBAC or ABAC

## Input Validation

- [ ] Validate all user input
- [ ] Use parameterized queries (prevent SQL injection)
- [ ] Sanitize output (prevent XSS)
- [ ] Validate file uploads

## API Security

- [ ] Use HTTPS everywhere
- [ ] Implement CORS properly
- [ ] Rate limit API endpoints
- [ ] Use API keys or OAuth

## Data Protection

- [ ] Encrypt sensitive data at rest
- [ ] Use TLS for data in transit
- [ ] Mask sensitive data in logs
- [ ] Implement data retention policies

## Headers

Set security headers:
- Content-Security-Policy
- X-Frame-Options
- X-Content-Type-Options
- Strict-Transport-Security