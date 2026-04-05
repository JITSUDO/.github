<p align="center">
  <img src="https://raw.githubusercontent.com/JITSUDO/.github/main/profile/jitsudo-wordmark.png" alt="JITSudo" width="320" />
</p>

<p align="center">
  <strong>Just-in-time access management for AWS.</strong><br/>
  Request, approve, and provision temporary elevated access with policy-driven authorization,<br/>
  full audit trails, and automatic expiration.
</p>

<p align="center">
  <a href="https://jitsudo.io"><img src="https://forthebadge.com/api/badges/generate?primaryLabel=%20&primaryBGColor=%23051121&secondaryLabel=jitsudo.io&secondaryBGColor=%23051121&secondaryTextColor=%2314B488&secondaryIcon=googlechrome&secondaryIconPosition=left&secondaryIconColor=%2314B488" alt="Website" /></a>
  <a href="https://docs.jitsudo.io"><img src="https://forthebadge.com/api/badges/generate?primaryLabel=%20&primaryBGColor=%23051121&secondaryLabel=docs.jitsudo.io&secondaryBGColor=%23051121&secondaryTextColor=%2314B488&secondaryIcon=readthedocs&secondaryIconPosition=left&secondaryIconColor=%2314B488" alt="Documentation" /></a>
</p>

---

### What is JITSudo?

JITSudo eliminates standing privileges in AWS. Instead of granting permanent elevated access, users request temporary access to specific resources — with a justification, a time limit, and a full audit trail. Policies written in [Cedar](https://www.cedarpolicy.com/) control who can access what, whether approval is required, and when access auto-expires.

**How it works:**

1. A user requests access to an AWS account or permission set
2. Cedar policies evaluate the request — auto-approve, require approval, or deny
3. An approver reviews and approves (or the policy auto-approves)
4. JITSudo provisions the IAM Identity Center assignment
5. Access expires automatically after the granted duration

### Key Features

- **Policy-driven authorization** — Cedar policies define who can access what, with fine-grained conditions
- **Automatic expiration** — grants expire after the requested duration, no manual cleanup
- **Break-glass access** — emergency bypass for incidents, fully audited
- **Multi-tenant** — manage multiple AWS organizations from a single deployment
- **Full audit trail** — every request, approval, grant, and revocation is logged
- **Infrastructure as code** — manage policies, users, and configuration via Terraform

---

### Repositories

| Repo | Description | | |
|------|-------------|---|---|
| [jitsudo](https://github.com/JITSUDO/jitsudo) | Core platform — API server, worker, frontend | ![Language](https://img.shields.io/github/languages/top/JITSUDO/jitsudo?style=flat-square) | ![Issues](https://img.shields.io/github/issues-raw/JITSUDO/jitsudo?style=flat-square&label=issues) |
| [jitsudo-docs](https://github.com/JITSUDO/jitsudo-docs) | Documentation site ([docs.jitsudo.io](https://docs.jitsudo.io)) | ![Language](https://img.shields.io/github/languages/top/JITSUDO/jitsudo-docs?style=flat-square) | ![Issues](https://img.shields.io/github/issues-raw/JITSUDO/jitsudo-docs?style=flat-square&label=issues) |
| [terraform-provider-jitsudo](https://github.com/JITSUDO/terraform-provider-jitsudo) | Terraform provider for managing JITSudo resources | ![Language](https://img.shields.io/github/languages/top/JITSUDO/terraform-provider-jitsudo?style=flat-square) | ![Issues](https://img.shields.io/github/issues-raw/JITSUDO/terraform-provider-jitsudo?style=flat-square&label=issues) |

---

### Get Involved

JITSudo is built in the open and we welcome contributions of all kinds — code, documentation, bug reports, feature ideas, and feedback.

- **Found a bug?** [Open an issue](https://github.com/JITSUDO/jitsudo/issues/new?template=bug_report.md) in the relevant repo
- **Have an idea?** [Request a feature](https://github.com/JITSUDO/jitsudo/issues/new?template=feature_request.md)
- **Want to contribute?** Read our [Contributing Guide](https://github.com/JITSUDO/.github/blob/main/CONTRIBUTING.md) to get started
- **Security concern?** See our [Security Policy](https://github.com/JITSUDO/.github/blob/main/SECURITY.md) for responsible disclosure

Whether you're fixing a typo in the docs, adding a Terraform resource, or building a new feature — every contribution matters.
