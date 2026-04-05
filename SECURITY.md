# Security Policy

## Supported Versions

| Version | Supported |
|---------|-----------|
| Latest release | Yes |
| Previous minor | Security fixes only |
| Older | No |

## Reporting a Vulnerability

**Do not open a public issue for security vulnerabilities.**

Email **security@jitsudo.io** with:

- Description of the vulnerability
- Steps to reproduce
- Potential impact
- Suggested fix (if any)

We will acknowledge receipt within 48 hours and provide an initial assessment within 5 business days.

## Disclosure Policy

- We follow coordinated disclosure — we ask that you give us reasonable time to address the issue before public disclosure.
- We will credit reporters in the security advisory (unless you prefer to remain anonymous).
- We aim to release fixes within 30 days of confirmed vulnerabilities.

## Scope

The following are in scope:

- JITSudo API server and worker
- JITSudo web frontend
- Terraform provider
- Authentication and authorization flows
- Data exposure or leakage

Out of scope:

- Social engineering
- Denial of service
- Issues in third-party dependencies (report upstream)
