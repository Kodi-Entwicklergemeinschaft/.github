# Security Policy

We take the security of the KODI – Kommunen Digital projects seriously. Because these
applications serve public-sector ("Kommune") users, responsible disclosure matters.

## Reporting a vulnerability

**Do not report security issues through public GitHub issues, discussions, or pull
requests.**

Instead, report privately using GitHub's **"Report a vulnerability"** button under the
**Security** tab of the affected repository (Private Vulnerability Reporting). This opens
a confidential channel with the maintainers.

Please include:

- The affected repository and version / commit.
- A description of the vulnerability and its impact.
- Steps to reproduce (proof-of-concept if possible).
- Any suggested remediation.

## What to expect

- We aim to acknowledge a valid report within a few business days.
- We will work with you to confirm the issue and prepare a fix.
- Please give us reasonable time to remediate before any public disclosure.

## Scope

Configuration mistakes in your own deployment (e.g. committing a real `.env`, weak
database passwords, exposed admin endpoints) are **your** responsibility, not a
vulnerability in these projects. The reference apps ship with placeholder configuration
only — always supply your own secrets and never commit them.
