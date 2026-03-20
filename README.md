# My CVEs

Check all CVEs with working PoCs on the blog: [blogs.tunelko.com/cve-list](https://blogs.tunelko.com/cve-list/)

## LiveHelperChat v4.81 (INCIBE-CNA)

| CVE | Vulnerability | CWE | CVSS v4.0 | Severity |
|-----|--------------|-----|-----------|----------|
| [CVE-2026-4380](CVE-2026-4380/) | Stored XSS via Content-Type manipulation | CWE-79 | 9.2 | CRITICAL |
| [CVE-2026-4381](CVE-2026-4381/) | Arbitrary file read via mass assignment | CWE-915 | 8.6 | HIGH |
| [CVE-2026-4382](CVE-2026-4382/) | Unsafe deserialization → RCE | CWE-502 | 7.7 | HIGH |
| [CVE-2026-4383](CVE-2026-4383/) | Authorization bypass (inverted logic) | CWE-863 | 7.1 | HIGH |
| [CVE-2026-4384](CVE-2026-4384/) | Missing authorization on webhook edit | CWE-862 | 7.1 | HIGH |
| [CVE-2026-4385](CVE-2026-4385/) | SSRF via incoming webhook | CWE-918 | 6.9 | MEDIUM |
| [CVE-2026-4386](CVE-2026-4386/) | IDOR chat metadata leak | CWE-862 | 5.3 | MEDIUM |

## Wallos v4.6.2

| CVE | Vulnerability | CWE | CVSS | Severity | GHSA |
|-----|--------------|-----|------|----------|------|
| CVE-2026-33400 | Stored XSS via payment method rename | CWE-79 | 5.4 | MEDIUM | [GHSA-p6v5-227f-f3fv](https://github.com/ellite/Wallos/security/advisories/GHSA-p6v5-227f-f3fv) |
| CVE-2026-33399 | SSRF bypass of CVE-2026-30839/30840 fix | CWE-918 | 7.7 | HIGH | [GHSA-mfjc-3258-cq3j](https://github.com/ellite/Wallos/security/advisories/GHSA-mfjc-3258-cq3j) |
| CVE-2026-33417 | Password reset tokens never expire | CWE-640 | 6.5 | MEDIUM | [GHSA-p3fv-m43r-3fhf](https://github.com/ellite/Wallos/security/advisories/GHSA-p3fv-m43r-3fhf) |

## Solidtime v0.11.5

| CVE | Vulnerability | CWE | CVSS | Severity | GHSA |
|-----|--------------|-----|------|----------|------|
| CVE-2026-33345 | IDOR on private projects | CWE-639 | 6.5 | MEDIUM | [GHSA-354j-rx28-jjxm](https://github.com/solidtime-io/solidtime/security/advisories/GHSA-354j-rx28-jjxm) |

## Disclaimer

All vulnerabilities were discovered during authorized security research on open-source software. Testing was performed exclusively against local Docker instances under the researcher's control. Disclosure was coordinated with vendors and/or INCIBE as Root CNA for Spain and GHSA.
