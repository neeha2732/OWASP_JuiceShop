# 🛡️ Penetration Testing Report – OWASP Juice Shop

## 📄 OWASP Juice Shop
**Black Box Penetration Test of OWASP Juice Shop**

---

## 📝 Short Description
This repository contains a black box penetration testing report for OWASP Juice Shop, one of the most insecure web applications designed for learning application security. This report includes identified vulnerabilities, risk ratings, tools used, and remediation suggestions following industry-standard methodologies.

---

## 🛠️ Tools Used
- **Burp Suite** (Community)
- **OWASP ZAP**
- **Nmap**
- **Nikto**
- **Kali Linux**
- **Wireshark**
- **Firefox Dev Tools**
- **Postman**

---

## 🧪 Test Methodology
The assessment followed the **OWASP Web Security Testing Guide (WSTG)** framework and standard black-box penetration testing practices:

1. **Reconnaissance**
2. **Mapping the Application**
3. **Vulnerability Discovery**
4. **Exploitation**
5. **Post-Exploitation & Reporting**

---


## 📊 Findings Summary

| Vulnerability Description                             | Likelihood | Impact  | Rating  | Status |
|--------------------------------------------------------|------------|---------|---------|--------|
| DOM XSS at Search Field                                | Medium     | Low     | Low     | Open   |
| SQL Injection in Login Form                            | Medium     | High    | High    | Open   |
| IDOR at Basket View                                    | Medium     | Medium  | Medium  | Open   |
| IDOR at Adding Items to Basket                         | Medium     | Medium  | Medium  | Open   |
| Business Logic in Chatbot                              | High       | Low     | Low     | Open   |
| IDOR at Customer Feedback                              | Medium     | High    | High    | Open   |
| Reflected XSS in Track-Result                          | Medium     | Medium  | Medium  | Open   |
| Stored XSS at Comment Field                            | Medium     | Critical| High    | Open   |
| Business Logic in Customer Feedback                    | Medium     | Low     | Low     | Open   |
| IDOR in Product Reviews                                | Medium     | Medium  | Medium  | Open   |
| Business Logic in Add to Basket                        | Medium     | High    | High    | Open   |
| Stored XSS at Email in Registration                    | High       | High    | High    | Open   |
| SQLi to Retrieve All User Data                         | High       | Low     | Low     | Open   |
| Upload of Invalid File Type (Complain Feature)         | High       | High    | High    | Open   |
| Upload File > 100KB in Complain                        | Medium     | Medium  | Medium  | Open   |
| Stored XSS in Username Field                           | Low        | High    | High    | Open   |
| Bruteforce Security Question                           | Low        | Medium  | Medium  | Open   |
| CSRF to Change User Password                           | Low        | Low     | Low     | Open   |
| Coupons File Exposure                                  | Low        | Low     | Low     | Open   |
| Package.json Backup Exposure                           | Low        | Low     | Low     | Open   |
| suspicious_errors File Exposure                        | Medium     | High    | High    | Open   |
| Access Logs Exposure                                   | Low        | Low     | High    | Open   |
| CSRF to Change Username                                | Low        | Low     | Low     | Open   |
| Stored XSS in Product Addition                         | Low        | High    | High    | Open   |
| Stored XSS at Last Login                               | Low        | High    | High    | Open   |
| Registering User as Admin                              | Medium     | High    | High    | Open   |
| CAPTCHA Bypass in Feedback                             | Medium     | Low     | Low     | Open   |
| Open Redirect                                          | Medium     | Low     | Low     | Open   |
| Blind SSRF via Image URL                               | Low        | High    | High    | Open   |


## 📎 Full Report

👉 [Click here to view the full report (PDF)](Report_Link.pdf)


---

---------------------------------------------------------------------------------------------------
