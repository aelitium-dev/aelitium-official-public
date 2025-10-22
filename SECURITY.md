# Security Policy

## Reporting Security Vulnerabilities

**DO NOT** open public GitHub issues for security vulnerabilities.

### Responsible Disclosure

If you discover a security vulnerability in AELITIUM, please report it to:

**Email:** security@aelitium.eu
**PGP Key:** Available at https://aelitium.eu/.well-known/pgp-key.txt

### What to Include

Please provide:

1. **Description** of the vulnerability
2. **Steps to reproduce** the issue
3. **Potential impact** assessment
4. **Suggested fix** (if available)
5. **Your contact information** for follow-up

### Response Timeline

- **Acknowledgment:** Within 48 hours
- **Initial Assessment:** Within 7 days
- **Resolution Target:** 30 days for critical issues, 90 days for non-critical
- **Public Disclosure:** Coordinated with reporter after fix deployment

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| 1.x     | :white_check_mark: |
| < 1.0   | :x:                |

## Security Measures

### Authentication & Authorization

- Multi-factor authentication (MFA) supported
- Role-based access control (RBAC)
- JWT-based API authentication
- API key rotation policies

### Data Protection

- AES-256 encryption for sensitive data at rest
- TLS 1.3 for all network communications
- GPG signing for audit bundles
- Multi-tenant data isolation

### Infrastructure Security

- Cloudflare DDoS protection
- Rate limiting on all public endpoints
- Security headers (HSTS, CSP, X-Frame-Options)
- Regular security audits and penetration testing

### Monitoring & Incident Response

- 24/7 security monitoring via Prometheus/Grafana
- Automated alerting for suspicious activity
- Incident response playbooks
- Regular security log reviews

## Vulnerability Disclosure Policy

AELITIUM follows responsible disclosure practices:

1. **Private Reporting:** Security issues reported privately
2. **Coordinated Disclosure:** Work with researcher on timeline
3. **Credit:** Recognition for responsible disclosure (if desired)
4. **CVE Assignment:** For eligible vulnerabilities
5. **Public Advisory:** After fix deployment

## Security Contacts

- **General Security:** security@aelitium.eu
- **Emergency Hotline:** Available to enterprise customers under NDA
- **Bug Bounty Program:** Contact security@aelitium.eu for program details

## Code of Conduct

Security researchers are expected to:

- Act in good faith
- Avoid privacy violations and data destruction
- Not disrupt AELITIUM services
- Provide reasonable time for remediation
- Maintain confidentiality until coordinated disclosure

---

**Last Updated:** 2025-10-22
**Policy Version:** 1.0
