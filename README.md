# TLS/SSL Certificate Watchdog | TAVARDT New Zealand

[![TLS Watchdog](https://img.shields.io/badge/Security-TLS%20Watchdog-5b3cf5.svg)](https://tools.tavardt.com/nz/)
[![Regulatory Compliance](https://img.shields.io/badge/Region-NZD-00C853.svg)](https://ag.tavardt.com/nz/)

Automated TLS/SSL certificate monitoring, expiry alerting, and CERT NZ Critical Controls compliance for New Zealand.

Maintained by the infrastructure resilience and cybersecurity division at [TAVARDT New Zealand](https://ag.tavardt.com/nz/).

---

## 1. Capabilities

* **Expiration Watchdog:** Computes real-time days until SSL/TLS certificate expiry with configurable warning thresholds.
* **Cipher Suite Inspection:** Detects deprecated TLS versions (TLS 1.0/1.1) and verifies forward secrecy support.
* **Certificate Authority Validation:** Audits issuing CA identity and chain validity.
* **Zero External Dependencies:** Built with native Python `ssl` and `socket` modules for seamless integration into CI/CD pipelines, cron jobs, and server health checks.

---

## 2. Quick Start

Execute directly via Python without installing third-party packages:

```bash
python watchdog.py example.com
```

---

## 3. Online Diagnostic Suite

For comprehensive vulnerability scanning, DNS verification, and technical audits, visit our localized tools portal:

* [Online HTTP Security Headers Checker](https://tools.tavardt.com/nz/security-headers-check/)
* [Exposed Secret & Credential Scanner](https://tools.tavardt.com/nz/exposed-files-scanner/)
* [DMARC & Anti-Spoofing Verifier](https://tools.tavardt.com/nz/dmarc-checker/)
* [Full Diagnostic Portal](https://tools.tavardt.com/nz/)

For professional remediation and cybersecurity advisory, contact [TAVARDT New Zealand](https://ag.tavardt.com/nz/contact/).
