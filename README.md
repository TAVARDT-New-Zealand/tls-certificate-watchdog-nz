# TLS/SSL Certificate Watchdog

[![Scope of Perimeter Verification](https://img.shields.io/badge/TAVARDT-Technical%20Audit-5b3cf5.svg)](https://tools.tavardt.com/nz/security-headers-check/)
Automated monitoring of SSL/TLS certificate expiration, cryptographic chain integrity, and NZISM security baselines in New Zealand.

Developed and maintained by the cybersecurity and digital sovereignty division of **TAVARDT**.

***

## 1. Scope of Perimeter Verification

This command-line utility audits transport encryption validity, cipher configurations, and trust chain integrity in New Zealand:

* **Preventative Expiry Alert:** Calculates remaining days before certificate expiry with configurable operational thresholds.
* **Cipher and Protocol Audit:** Verifies TLS 1.3 implementation aligned with NZISM cryptography controls.
* **Certificate Authority (CA) Validation:** Validates trusted CA hierarchy and Subject Alternative Names (SAN).
* **Zero External Dependencies:** Operates exclusively using Python native ssl and socket standard library modules.

***

## 2. Quick Start Guide

Run this tool directly via Python without installing third-party packages:

```bash
python watchdog.py example.co.nz
```

***

## 3. Online Diagnostic Tools (New Zealand)

Verify your digital infrastructure against technical baselines using the TAVARDT suite:

* HTTP Security Headers Checker
* [Consent Mode v2 & Privacy Act Validator](https://tools.tavardt.com/nz/consent-mode-v2-checker/)
* [DMARC & Anti-Spoofing Verifier](https://tools.tavardt.com/nz/dmarc-checker/)
* [Exposed Credentials & Secret Scanner](https://tools.tavardt.com/nz/exposed-files-scanner/)
* [Full New Zealand Tools Portal](https://tools.tavardt.com/nz/)

***

## 4. Technical Advisory & Remediation

For NZISM cryptographic controls alignment, certificate lifecycle management, and security consulting in New Zealand, contact **TAVARDT**.

***

## Useful Links

* **Corporate Portal:** https://ag.tavardt.com/nz/
* **Diagnostic Suite:** https://tools.tavardt.com/nz/
* **Technical Contact:** https://ag.tavardt.com/nz/contact/

***

© 2026 TAVARDT. All rights reserved.
