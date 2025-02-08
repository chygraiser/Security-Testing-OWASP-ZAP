# 🚀 Security Testing with OWASP ZAP  

This repository contains **OWASP ZAP** security test reports and scripts for detecting web vulnerabilities.  

## 📌 Tools & Technologies  
- **OWASP ZAP** – Automated security scanning  
- **Burp Suite** – Manual security testing  
- **Common Vulnerabilities** – XSS, SQL Injection, CSRF  

## 📊 How to Run OWASP ZAP Scan  
1. Install **OWASP ZAP**  
2. Run an automated scan using CLI:  
   ```bash
   zap.sh -quickurl http://yourwebsite.com -quickout zap_report.html
