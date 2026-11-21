# Security Policy

## Scope & Confidentiality Rule

This repository contains **exclusively personal lab research, public dataset analyses, and authorized training platform writeups (TryHackMe / HackTheBox)**.

- **Zero Employer Data:** No client names, production IP addresses, internal hostnames, proprietary log samples, detection rules, or architectures from any employer are stored in this repository.
- **Sanitization:** All lab IP addresses use RFC 1918 private ranges (`10.0.0.0/8`, `172.16.0.0/12`, `192.168.0.0/16`) or documentation ranges (`192.0.2.0/24`, `198.51.100.0/24`, `203.0.113.0/24`).

## Automated Secret Scanning

Every push and pull request is scanned via GitHub Actions using **Gitleaks** (`.github/workflows/gitleaks.yml`).

## Reporting a Security or Confidentiality Issue

If you believe you have found an inadvertently committed secret, vulnerability, or policy issue in this repository:

1. **Do not** open a public GitHub issue if it exposes a sensitive secret.
2. Contact **Abdelghani Demmouche** directly via the contact email listed on the [GitHub Profile](https://github.com/boughaniLabo).
