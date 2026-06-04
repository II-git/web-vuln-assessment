# Web Application Vulnerability Assessment

Manual web application security assessment using Burp Suite, targeting business logic and information disclosure vulnerabilities through PortSwigger Web Security Academy labs.

## Tools Used

- Burp Suite (Proxy, Repeater, Scope)
- PortSwigger Web Security Academy

## Findings Summary

| Lab | Vulnerability Type | Severity | OWASP Reference | Tool Used |
|-----|--------------------|----------|-----------------|-----------|
| 1 | Business Logic (Price Manipulation) | High | A04 - Insecure Design | Burp Proxy |
| 2 | Information Disclosure (Stack Trace) | Medium | A05 - Security Misconfiguration | Burp Repeater |

## Labs

- [Lab 1 - Business Logic Vulnerability](lab-01-business-logic/writeup.md)
- [Lab 2 - Information Disclosure](lab-02-info-disclosure/writeup.md)