# VAPT Report for example.com

**Date:** 2026-01-24 18:21:32

# Security Score: 55/100 (Grade: F)

## Executive Summary
| Severity | Count |
|---|---|
| CRITICAL | 0 |
| HIGH | 1 |
| MEDIUM | 2 |
| LOW | 2 |

---
## Detailed Findings
### [HIGH] Missing Header: Strict-Transport-Security
The security header Strict-Transport-Security is missing from the response. Ensure communication happens over HTTPS.

### [MEDIUM] Missing Header: Content-Security-Policy
The security header Content-Security-Policy is missing from the response. Restrict sources for content (scripts, images, etc.) to prevent XSS.

### [MEDIUM] Missing Header: X-Frame-Options
The security header X-Frame-Options is missing from the response. Prevent clickjacking by denying or restricting iframe embedding.

### [LOW] Missing Header: X-Content-Type-Options
The security header X-Content-Type-Options is missing from the response. Prevent MIME-sniffing.

### [LOW] Missing Header: Referrer-Policy
The security header Referrer-Policy is missing from the response. Control how much referrer information is included with requests.


---
## Raw Module Data
<details><summary><b>Header Analysis</b></summary>

**Missing Headers**:
- Strict-Transport-Security
- Content-Security-Policy
- X-Frame-Options
- X-Content-Type-Options
- Referrer-Policy

**Present Headers**:

</details>

<details><summary><b>Port Scan Results</b></summary>

No open ports found (in top 100 scan) or firewall blocking.

</details>

