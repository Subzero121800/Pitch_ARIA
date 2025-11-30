# Security Policy

## Scope

This repository contains **static HTML/CSS investor presentation materials** hosted on GitHub Pages. It does not contain:

- Production ARIA platform source code
- Executable software or binaries
- Authentication systems or user data
- API endpoints or backend services
- Database connections or credentials

## What Is In Scope

Security reports are accepted for:

- Cross-site scripting (XSS) vulnerabilities in the static site
- Exposed sensitive information (accidentally committed credentials, API keys, etc.)
- Malicious code injection in HTML/CSS/JavaScript
- Privacy concerns with presented content

## What Is Out of Scope

The following are **not in scope** for this repository:

- Vulnerabilities in the ARIA platform itself (report separately—see below)
- GitHub Pages infrastructure issues (report to GitHub)
- Third-party dependencies or CDN issues
- Social engineering attacks
- Denial of service

## Reporting a Vulnerability

### For This Repository (Investor Site)

If you discover a security issue in this investor presentation site:

1. **Do not** open a public issue
2. **Email:** joseph@resilientmindai.com
3. **Subject:** "Security Report - Pitch_ARIA Site"
4. Include:
   - Description of the vulnerability
   - Steps to reproduce
   - Potential impact
   - Any suggested remediation

### For the ARIA Platform

If you believe you have discovered a vulnerability in the ARIA platform itself (not this presentation site):

1. **Email:** joseph@resilientmindai.com
2. **Subject:** "Security Report - ARIA Platform"
3. Provide detailed reproduction steps

## Responsible Disclosure

We follow a **90-day responsible disclosure policy**:

1. Upon receiving a valid report, we will acknowledge receipt within 48 hours
2. We will investigate and provide an initial assessment within 14 days
3. We aim to remediate confirmed vulnerabilities within 90 days
4. We will notify the reporter when the issue is resolved
5. Public disclosure may occur after remediation, coordinated with the reporter

## Platform Status

**ARIA is an evolving research and production operating system.** The platform is under active development with:

- Ongoing security audits and remediation
- Compliance work for DoD, HIPAA, and GDPR requirements
- Continuous improvement of the autonomous recovery and compliance subsystems

The investor materials presented in this repository reflect the current state of development and architectural decisions. Production deployment status varies by component and is discussed in direct investor communications.

## Recognition

We appreciate security researchers who help improve our materials. With your permission, we will acknowledge your contribution in our release notes or security advisories.

## Contact

**Joseph C. McGinty Jr.**
Chief Innovation Officer
ResilientMind AI

- **Email:** joseph@resilientmindai.com
- **Phone:** 724-248-1750

---

© 2025 Joseph C. McGinty Jr. All rights reserved.
