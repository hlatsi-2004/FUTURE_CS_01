 TASK 1
 
🔐 TagBack – Vulnerability Assessment Report

📌 Overview

This repository contains a security vulnerability assessment of the TagBack platform — a web application designed to help users report and recover lost and found items.

The purpose of this project is to evaluate the security posture of the website using ethical, read-only analysis techniques and provide clear, business-friendly recommendations.

🎯 Objectives

- Identify common web security vulnerabilities

- Classify risks (Low / Medium / High)

- Explain issues in simple terms

- Provide practical remediation steps

- Present findings in a professional security report

⚠️ Scope & Ethics

This assessment follows ethical security practices.

🔍 Key Findings Summary

Risk Level	Issues Identified

🔴 High	Missing security headers, insecure cookies

🟠 Medium	Outdated libraries, info disclosure, no rate limiting

🟢 Low	Weak error handling messages

📄 Full Report

👉 The detailed vulnerability assessment report is available

It includes:

Detailed findings
Risk classification
Business-friendly explanations
Remediation recommendations

📸 Evidence

Screenshots and tool outputs are available in the /evidence folder.


📌 Conclusion

This assessment highlights key security improvements needed to strengthen the TagBack platform. Addressing these issues will significantly improve user safety, trust, and system resilience.

TASK 2

# PhishGuard - Phishing Detection & Awareness Tool

## 📌 Project Overview

PhishGuard is a phishing email analysis tool built as part of a SOC analyst simulation. It helps identify malicious emails and educates users on how to avoid phishing attacks.

**Goal:** Analyze real phishing emails, identify red flags, classify risk, and create professional awareness reports that businesses can actually use.

---

## 🔍 What This Tool Does

| Feature | Description |
|---------|-------------|
| Email Analysis | Analyzes subject, body, and sender for phishing indicators |
| Red Flag Detection | Identifies fake domains, urgency language, generic greetings, suspicious links |
| Risk Classification | Labels email as 🔴 Phishing / 🟡 Suspicious / 🟢 Safe |
| Report Generation | Exports findings as a professional PDF report |
| Awareness Guide | Provides do's and don'ts for employees |

---

## 📧 Sample Email Analyzed

**Subject:** ⚠️ Urgent: Your Account Will Be Locked

**Sender:** security@secure-account-verify.com (FAKE)

**Body:**
> Dear User,
>
> We noticed suspicious activity on your account. To avoid suspension, verify your details immediately.
>
> Verify Now: http://secure-account-verify.com
>
> Failure to verify within 24 hours will result in permanent account lock.

---

## 🚩 Phishing Indicators Found

| Indicator | Found? | Explanation |
|-----------|--------|-------------|
| Fake sender domain | ✅ | @secure-account-verify.com not legitimate |
| Urgency language | ✅ | "24 hours" and "permanent lock" create panic |
| Generic greeting | ✅ | "Dear User" instead of real name |
| Suspicious link | ✅ | Link domain mismatches legitimate company |

---

## 📊 Risk Classification


**Reason:** Direct attempt to steal credentials via fake login page.

---

## ✅ Prevention Tips for Employees

### Do's
- Hover over links before clicking
- Check sender's full email address
- Report suspicious emails to security team

### Don'ts
- Don't panic at urgent words like "immediately" or "24 hours"
- Don't click links from unknown senders
- Don't reply with your password — ever

---

## 🛠️ Tools Used in This Analysis

| Tool | Purpose |
|------|---------|
| PhishGuard Detection Engine | Automated red flag identification |
| Google Message Header Analyzer | Header validation (optional reference) |
| Public Phishing Datasets | Real email samples for testing |

---

## 📁 Sample Sources

Real phishing email samples referenced from:
- [Phishing Pot Repository](https://github.com/rf-peixoto/phishing_pot)
- [Phishing Mail Examples](https://github.com/autinerd/phishing-mail-examples)

---

## 📄 Deliverables

- [x] Phishing email analysis completed
- [x] Red flags identified
- [x] Risk classification assigned
- [x] Prevention guidelines written
- [x] PDF report generated

---

## 👤 Author

Security Analyst - Phishing Detection & Awareness Project

---

## ⚠️ Disclaimer

This project was completed for educational purposes as part of a cybersecurity training task. No illegal activity was conducted. All samples analyzed are from public datasets.


