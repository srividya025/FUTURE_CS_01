# Web Application Security Assessment using Nmap and OWASP ZAP

## Internship Task – Web Security Testing

This repository contains the results of a web application vulnerability assessment conducted as part of my cybersecurity internship task.

---

## 🎯 Objective
To perform vulnerability assessment on a publicly available demo web application using industry-standard security tools.

---

## 🌐 Target Website
**Demo Testfire Application**  
http://testphp.vulnweb.com

---

## 🛠️ Tools Used
- Nmap (Network Scanning)
- OWASP ZAP (Vulnerability Scanner)
- Browser Developer Tools
- AJAX Spider (Application Crawling)

---

## 🔍 Testing Activities
- Network port scanning using Nmap  
- Automated vulnerability scanning using OWASP ZAP  
- AJAX Spider crawling for dynamic content  
- HTTP header inspection using Browser Developer Tools  

---

## 🚨 Vulnerabilities Observed
The scan identified the following issues:

- Missing Content Security Policy (CSP) Header  
- Missing Anti-Clickjacking Header  
- Cookie without HttpOnly flag  
- Timestamp Disclosure  
- Security header configuration weaknesses  

**Note:**  
No high-risk vulnerabilities were detected. The identified issues were primarily medium and low risk.

---

## 📂 Repository Contents
- Vulnerability Assessment Report (PDF)  
- Nmap scan results  
- OWASP ZAP scan screenshots  
- Browser DevTools analysis screenshots  
- AJAX Spider crawl results  

All screenshots are stored inside the `screenshots/` folder.

---

## ✅ Recommendations
To improve the security posture of the web application, the following measures are recommended:

- Implement Content Security Policy (CSP) headers to prevent XSS attacks  
- Enable Anti-Clickjacking protection using `X-Frame-Options` or CSP  
- Configure cookies with `HttpOnly` and `Secure` flags  
- Disable or hide server timestamp information  
- Apply proper security headers across all pages  
- Perform regular vulnerability assessments  
- Keep web servers and applications updated with security patches  

---

## ⚠️ Disclaimer
This assessment was conducted **only on a publicly available demo application** and strictly for **educational purposes**.
