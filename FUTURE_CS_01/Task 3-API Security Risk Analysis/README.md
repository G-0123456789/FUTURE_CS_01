# 🔐 API Security Risk Analysis

### Cyber Security Task 3 – Future Interns (2026)

---

## 📌 Overview

This repository contains an API Security Risk Analysis Report conducted on a public API as part of the Future Interns Cyber Security Program.

The purpose of this project is to evaluate common API security risks using read-only testing methods and present findings in a professional, business-friendly format.

---

## 🌐 Target API

* https://jsonplaceholder.typicode.com

---

## 🎯 Objective

* Analyze API endpoints and responses
* Identify common API security risks
* Evaluate authentication and access control
* Classify risks based on severity
* Provide clear and actionable remediation steps

---

## ⚖️ Scope & Ethics

This assessment was conducted under strict ethical guidelines:

### ✅ Allowed

* Read-only API requests (GET)
* Testing public/demo endpoints
* Header and response inspection

### ❌ Not Allowed

* Exploitation or bypass attempts
* Denial-of-Service (DoS) testing
* Attacking private or production APIs

---

## 🛠️ Tools Used

* **Postman** – API request testing and response analysis
* **Browser Developer Tools** – Header and response inspection

---

## 🔍 Key Findings

| # | Risk                             | Severity |
| - | -------------------------------- | -------- |
| 1 | No Authentication Required       | High     |
| 2 | Excessive Data Exposure          | Medium   |
| 3 | No Rate Limiting                 | Medium   |
| 4 | Predictable Resource Access      | Medium   |
| 5 | Weak Input Validation Indicators | Low      |

---

## ⚠️ Risk Summary

The API demonstrates several common security weaknesses typically found in poorly secured production systems:

* Public access to all endpoints without authentication
* Exposure of complete datasets
* Lack of request limiting controls
* Predictable resource identifiers

---

## 🧠 How the Risk Works

APIs without proper security controls can be abused by attackers to:

* Extract large volumes of data
* Enumerate users and resources
* Overload systems with excessive requests
* Access sensitive information without authorization

---

## 🛡️ Recommendations

* Implement authentication (API keys, OAuth, JWT)
* Restrict data exposure to necessary fields only
* Apply rate limiting to prevent abuse
* Enforce proper authorization checks
* Validate and sanitize all inputs
* Monitor API activity and logs

---

## 📄 Report

👉 [Download Full Report](./API%20Security%20Report.pdf)

---

## 📸 Evidence Included

* Postman request screenshots
* API endpoint testing results
* Response data analysis

---

## 📚 Skills Demonstrated

* API Security Analysis
* Risk Identification & Classification
* Use of API Testing Tools (Postman)
* Secure API Design Understanding
* Business-Oriented Security Reporting

---

## 🚀 Author

**Given Dumisa**
Cyber Security Student | Future Interns Program

---

## 📢 Notes

This assessment was conducted for educational purposes only using a public test API.
No harmful or intrusive actions were performed.

---

## 🌟 Showcase

This project demonstrates the ability to perform real-world API security assessments, similar to services offered by:

* SaaS security teams
* Cybersecurity agencies
* Application Security (AppSec) professionals

---
