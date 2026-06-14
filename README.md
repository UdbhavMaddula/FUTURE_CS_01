# Future Interns – Cyber Security Task 1

## Vulnerability Assessment Report for a Live Website (Read-Only Scope)

This repository contains my submission for **Future Interns Cyber Security Task 1**, where I conducted a passive vulnerability assessment of a public demo web application while adhering to strict ethical guidelines.

---

## Objective

The objective of this task was to evaluate the security posture of a publicly accessible website by identifying common security weaknesses through non-intrusive techniques.

The assessment focused on:

- Identifying publicly observable vulnerabilities
- Classifying risks based on severity
- Explaining findings in business-friendly language
- Recommending practical remediation measures
- Preparing a professional vulnerability assessment report

---

## Target Application

- **Website:** https://demo.testfire.net
- **Application:** Altoro Mutual (IBM Demo Banking Application)

> This is an intentionally vulnerable demonstration application designed for security learning and testing purposes.

---

## Scope

### Included

- Public-facing pages
- Passive analysis
- Security header review
- Service enumeration
- Browser-based inspection
- Read-only assessment

### Excluded

- Exploitation attempts
- Login bypass
- Brute-force attacks
- Denial-of-Service (DoS)
- Active exploitation
- Any activity that could impact the application's availability

---

## Tools Used

- **OWASP ZAP**
  - Passive vulnerability identification
  - Security header analysis
  - Alert generation

- **Nmap / Zenmap**
  - Service enumeration
  - Port discovery
  - Version detection

- **Browser Developer Tools**
  - Response header inspection
  - Cookie analysis
  - Client-side observations

- **Microsoft Word**
  - Professional report preparation

---

## Findings Summary

| Severity | Count |
|-----------|--------|
| Medium | 6 |
| Low | 3 |
| Informational | 3 |

### Key Findings

- Absence of Anti-CSRF Tokens
- Content Security Policy (CSP) Header Not Set
- Missing Anti-Clickjacking Header
- Cookie Without SameSite Attribute
- Secure Pages Including Mixed Content
- Strict-Transport-Security (HSTS) Header Missing
- Server Version Information Disclosure
- X-Content-Type-Options Header Missing
- Cache-Control Directive Review Required
- Timestamp Disclosure
- Suspicious Comments Identified
- Session Management Information Disclosure

---

## Deliverables

This repository includes:

- Vulnerability Assessment Report (PDF)
- Documentation of methodology and findings

---

## Ethical Statement

This assessment was conducted strictly within authorized and read-only boundaries.

No intrusive testing techniques were used. No attempts were made to exploit vulnerabilities or disrupt the application's normal operation.

The purpose of this assessment was educational and focused on understanding how passive vulnerability assessments are performed in professional security consulting engagements.

---

## Learning Outcomes

Through this task, I gained practical experience in:

- Conducting passive web application assessments
- Using OWASP ZAP for vulnerability discovery
- Performing service enumeration using Nmap
- Reviewing security headers using Browser DevTools
- Documenting vulnerabilities professionally
- Communicating security findings in a business-friendly manner

---

## Repository Structure

```
FUTURE_CS_01/
├── README.md
└── future_cs_1.pdf
```

---

## Author

**Maanas Sri Udbhav Maddula**

B.E. CSE (Cyber Security)  
Chandigarh University

- TryHackMe Top 5%

---

### Future Interns – Cyber Security Track

This project was completed as part of the **Future Interns Cyber Security Program** to develop practical vulnerability assessment and reporting skills aligned with industry practices.
