🔐 TagBack – Vulnerability Assessment Report
📌 Overview

This repository contains a security vulnerability assessment of the TagBack platform — a web application designed to help users report and recover lost and found items.

The purpose of this project is to evaluate the security posture of the website using ethical, read-only analysis techniques and provide clear, business-friendly recommendations.

🎯 Objectives
Identify common web security vulnerabilities
Classify risks (Low / Medium / High)
Explain issues in simple terms
Provide practical remediation steps
Present findings in a professional security report
⚠️ Scope & Ethics

This assessment follows ethical security practices.

✅ Allowed:
Public website analysis
Passive scanning (headers, frontend, cookies)
Non-intrusive inspection
❌ Not Allowed:
Exploitation or hacking attempts
Brute-force attacks
Login bypass testing
Any harmful actions against the system
🛠️ Tools Used
OWASP ZAP (Passive Scan)
Nmap (Basic port analysis)
Browser DevTools (Headers & cookies inspection)
Canva (Final report design)
🔍 Key Findings Summary
Risk Level	Issues Identified
🔴 High	Missing security headers, insecure cookies
🟠 Medium	Outdated libraries, info disclosure, no rate limiting
🟢 Low	Weak error handling messages
📄 Full Report

👉 The detailed vulnerability assessment report is available here:

📎 TagBack_Vulnerability_Report.pdf

It includes:

Detailed findings
Risk classification
Business-friendly explanations
Remediation recommendations
📸 Evidence

Screenshots and tool outputs are available in the /evidence folder.

Examples:

HTTP security headers analysis
OWASP ZAP passive scan results
Browser DevTools inspection
🧠 Key Security Insights
Security headers are critical for preventing browser-based attacks
Session cookies must be properly secured to prevent hijacking
Outdated libraries increase exposure to known vulnerabilities
Even small misconfigurations can lead to serious risks
🚀 Recommendations
Implement strict Content Security Policy (CSP)
Secure cookies using HttpOnly + Secure + SameSite
Update all frontend dependencies
Add rate limiting for sensitive endpoints
Improve error handling to avoid information leakage
📌 Conclusion

This assessment highlights key security improvements needed to strengthen the TagBack platform. Addressing these issues will significantly improve user safety, trust, and system resilience.

