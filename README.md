# My CVEs

Check all CVEs with working PoCs on the blog: [blogs.tunelko.com/cve-list](https://blogs.tunelko.com/my-cve-list/)

## LiveHelperChat v4.81 (INCIBE-CNA)

| CVE | Vulnerability | CWE | CVSS v4.0 | Severity |
|-----|--------------|-----|-----------|----------|
| [CVE-2026-4380](LiveHelperChat/CVE-2026-4380/) | Stored XSS via Content-Type manipulation | CWE-79 | 9.2 | CRITICAL |
| [CVE-2026-4381](LiveHelperChat/CVE-2026-4381/) | Arbitrary file read via mass assignment | CWE-915 | 8.6 | HIGH |
| [CVE-2026-4382](LiveHelperChat/CVE-2026-4382/) | Unsafe deserialization → RCE | CWE-502 | 7.7 | HIGH |
| [CVE-2026-4383](LiveHelperChat/CVE-2026-4383/) | Authorization bypass (inverted logic) | CWE-863 | 7.1 | HIGH |
| [CVE-2026-4384](LiveHelperChat/CVE-2026-4384/) | Missing authorization on webhook edit | CWE-862 | 7.1 | HIGH |
| [CVE-2026-4385](LiveHelperChat/CVE-2026-4385/) | SSRF via incoming webhook | CWE-918 | 6.9 | MEDIUM |
| [CVE-2026-4386](LiveHelperChat/CVE-2026-4386/) | IDOR chat metadata leak | CWE-862 | 5.3 | MEDIUM |

## Pandora FMS Community v7.0NG.777 (Pandora FMS CNA / INCIBE)
 
| CVE | Vulnerability | CWE | CVSS v4.0 | Severity |
|-----|--------------|-----|-----------|----------|
| [CVE-2026-30807](PandoraFMS/CVE-2026-30807/) | API v2 Server Identifier Token Authentication Bypass | CWE-287 | 9.3 | CRITICAL |
| [CVE-2026-30808](PandoraFMS/CVE-2026-30808/) | API Authentication Bypass via Insecure Default | CWE-1188 | 9.3 | CRITICAL |
| [CVE-2026-30805](PandoraFMS/CVE-2026-30805/) | SSRF via API Checker (IP ACL bypass) | CWE-918 | 8.7 | HIGH |
| [CVE-2026-30806](PandoraFMS/CVE-2026-30806/) | OS Command Injection in Whois (Network Report) | CWE-78 | 8.7 | HIGH |
| [CVE-2026-30809](PandoraFMS/CVE-2026-30809/) | OS Command Injection in WebServerModuleDebug | CWE-78 | 8.7 | HIGH |
| [CVE-2026-30813](PandoraFMS/CVE-2026-30813/) | SQL Injection in Module Search | CWE-89 | 8.7 | HIGH |
| [CVE-2026-34186](PandoraFMS/CVE-2026-34186/) | SQL Injection in Custom Fields | CWE-89 | 8.7 | HIGH |
| [CVE-2026-30804](PandoraFMS/CVE-2026-30804/) | RCE via Extension Upload | CWE-434 | 8.6 | HIGH |
| [CVE-2026-30811](PandoraFMS/CVE-2026-30811/) | Missing Authorization in config endpoint | CWE-862 | 8.4 | HIGH |
| [CVE-2026-34188](PandoraFMS/CVE-2026-34188/) | OS Command Injection in Event Response | CWE-78 | 7.5 | HIGH |
| [CVE-2026-30810](PandoraFMS/CVE-2026-30810/) | Session Fixation (no `session_regenerate_id`) | CWE-384 | 7.3 | HIGH |
| [CVE-2026-34187](PandoraFMS/CVE-2026-34187/) | CSRF on Extension Pages | CWE-352 | 6.9 | MEDIUM |
| [CVE-2026-30812](PandoraFMS/CVE-2026-30812/) | Stored XSS in Event Comments | CWE-79 | 2.1 | LOW |

## Wallos v4.6.2

| CVE | Vulnerability | CWE | CVSS | Severity | GHSA |
|-----|--------------|-----|------|----------|------|
| [CVE-2026-33399](Wallos/CVE-2026-33399/) | SSRF bypass of CVE-2026-30839/30840 fix | CWE-918 | 7.7 | HIGH | [GHSA-mfjc-3258-cq3j](https://github.com/ellite/Wallos/security/advisories/GHSA-mfjc-3258-cq3j) |
| [CVE-2026-33417](Wallos/CVE-2026-33417/) | Password reset tokens never expire | CWE-640 | 6.5 | MEDIUM | [GHSA-p3fv-m43r-3fhf](https://github.com/ellite/Wallos/security/advisories/GHSA-p3fv-m43r-3fhf) |
| [CVE-2026-33400](Wallos/CVE-2026-33400/) | Stored XSS via payment method rename | CWE-79 | 5.4 | MEDIUM | [GHSA-p6v5-227f-f3fv](https://github.com/ellite/Wallos/security/advisories/GHSA-p6v5-227f-f3fv) |

## Solidtime v0.11.5

| CVE | Vulnerability | CWE | CVSS | Severity | GHSA |
|-----|--------------|-----|------|----------|------|
| [CVE-2026-33345](Solidtime/CVE-2026-33345/) | IDOR on private projects | CWE-639 | 6.5 | MEDIUM | [GHSA-354j-rx28-jjxm](https://github.com/solidtime-io/solidtime/security/advisories/GHSA-354j-rx28-jjxm) |

## MobaXterm Personal Edition Portable (Mobatek / INCIBE-CNA)

| CVE | Vulnerability | CWE | CVSS v4.0 | Severity |
|-----|--------------|-----|-----------|----------|
| [CVE-2026-11879](Mobatek/CVE-2026-11879/) | DLL search-order hijacking via predictable TEMP extraction dir (VERSION.dll / WINMM.dll) | CWE-427 | 8.5 | HIGH |

## Adobe Acrobat / Reader

| CVE | Vulnerability | CWE | CVSS 3.1 | Severity | Reference |
|-----|--------------|-----|----------|----------|-----------|
| [CVE-2026-47937](Adobe/CVE-2026-47937/) | Arbitrary code execution via DLL search-order hijacking (users32.dll) | CWE-427 | 7.4 | CRITICAL | [APSB26-63](https://helpx.adobe.com/security/products/acrobat/apsb26-63.html) |

**Stats:** 26 CVEs across 6 products: 4 CRITICAL + 15 HIGH + 6 MEDIUM + 1 LOW

**List updated:** This repo will be updated frequently 

## Disclaimer

All vulnerabilities were discovered during authorized security research on open-source software. Testing was performed exclusively against local Docker instances under the researcher's control. Disclosure was coordinated with vendors and/or INCIBE as Root CNA for Spain and GHSA.
