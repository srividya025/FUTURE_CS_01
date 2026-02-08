# FUTURE_CS_01
Web Application Security Assessment using Nmap and OWASP ZAP
Internship Task – Web Security Testing
This repository contains the results of a web application vulnerability assessment conducted as part of my cybersecurity internship task.

Objective
To perform vulnerability assessment on a publicly available demo web application using industry-standard security tools.

Target Website
Demo Testfire Application
http://testphp.vulnweb.com

Tools Used
Nmap (Network Scanning)
OWASP ZAP (Vulnerability Scanner)
Browser Developer Tools
AJAX Spider (Application Crawling)
Testing Activities
Network port scanning using Nmap
Automated vulnerability scanning using OWASP ZAP
AJAX Spider crawling for dynamic content
HTTP header inspection using Browser DevTools
Vulnerabilities Observed
The scan identified the following issues:

Missing Content Security Policy Header
Missing Anti-clickjacking Header
Cookie without HttpOnly flag
Timestamp Disclosure
Security header configuration weaknesses
No High-risk vulnerabilities were detected during testing. Issues observed were mainly medium and low risk.

Repository Contents
Vulnerability Assessment Report (PDF)
Nmap scan results
OWASP ZAP scan screenshots
Browser DevTools analysis screenshots
AJAX Spider crawl results
All screenshots are stored inside the screenshots/ folder.

Recommendations
To improve the security posture of the web application, the following measures are recommended:

Implement Content Security Policy (CSP) headers to prevent cross-site scripting attacks.
Enable Anti-clickjacking protection using X-Frame-Options or CSP frame restrictions.
Configure cookies with HttpOnly and Secure flags to prevent client-side access.
Disable or hide server timestamp information to reduce information disclosure.
Implement proper security headers configuration across all pages.
Regularly perform vulnerability assessments and security testing.
Keep web server and application components updated with security patches.
Disclaimer
This assessment was conducted only on a publicly available demo application for educational purposes.
