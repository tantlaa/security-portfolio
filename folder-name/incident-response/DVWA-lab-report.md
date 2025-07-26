# Penetration Testing Lab Report - DVWA

## Environment
- DVWA (Damn Vulnerable Web Application)
- Kali Linux, Burp Suite, SQLMap

## Vulnerabilities Exploited
- SQL Injection
- XSS (Reflected and Stored)
- Command Injection
- CSRF

## Methodology
1. Intercept requests using Burp Suite.
2. Exploit SQL injection via login form using `' OR 1=1 --`.
3. Inject `<script>alert('XSS')</script>` into form fields.
4. Capture request tokens for CSRF testing.

## Outcome
- Able to gain admin panel access
- Simulated data exfiltration
- Recommendations documented for mitigation

---

**Author:** Amna Siddiqui  
**Date:** July 2025
