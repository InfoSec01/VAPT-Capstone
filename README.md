
# 🔐 Vulnerability Assessment & Penetration Testing (VAPT) Capstone Project

**Author**: Baratul Khan  
**Bootcamp**: Auburn University Cybersecurity Program  
**Tools Used**: Kali Linux · Metasploit · Nmap · OpenVAS · Burp Suite · sqlmap · John the Ripper · OWASP ZAP  
**Duration**: October 29 – November 4, 2024

---

## 🚀 Project Summary

This project is a complete end-to-end penetration testing simulation on three targets:
- **Zero Bank** – Corporate environment using Windows 7
- **Application Server** – Hosting DVWA (Damn Vulnerable Web App)
- **Mutillidae** – OWASP testing web app

I performed **ethical hacking**, identified **59+ vulnerabilities**, and delivered a detailed security assessment report with **short- and long-term remediation strategies**.

---

## 🧪 Key Techniques & Findings

| Vulnerability | Risk | Tools Used | Summary |
|--------------|------|------------|---------|
| **EternalBlue Exploit** | Critical | Nmap, OpenVAS, Metasploit | Gained system-level access via MS17-010 |
| **Malware/Firewall Bypass** | Critical | msfvenom, Python HTTP server | Deployed reverse shell and disabled firewall |
| **Privilege Escalation** | Critical | SSH, Metasploit | Escalated from user to SYSTEM access |
| **Password Hashdump & Cracking** | Critical | Metasploit, John the Ripper | Recovered plaintext passwords |
| **SQL Injection** | High | sqlmap | Dumped entire user and credit card databases |
| **XSS & Directory Traversal** | High | DVWA, Burp Suite | Stole cookies and accessed `/etc/passwd` |
| **FTP Exploit (vsftpd 2.3.4)** | High | Metasploit | Gained root shell access via FTP |
| **OWASP-ZAP Scan** | High | OWASP ZAP | Identified additional 17+ critical vulnerabilities |

---

## 📸 Screenshots

| EternalBlue Exploit | SQL Injection | Firewall Disabled |
|---------------------|----------------|-------------------|
|<img width="542" alt="EternalBlue Exploit" src="https://github.com/user-attachments/assets/d7cf7445-f186-4adc-8b74-b728b5e39049" />|
|<img width="538" alt="SQLi and Blind SQLi" src="https://github.com/user-attachments/assets/8f7d9457-a9b3-44bf-84fa-c7c88c6d9ad5" />|
|<img width="538" alt="Firewall Malware Exploit" src="https://github.com/user-attachments/assets/baacbd7f-c436-4060-917a-4771ff816ada" />|

---

## 📄 Full Report & Presentation

- [📝 Final Report (PDF)](./)
- [🎯 Capstone Presentation Slides (PDF)](./reports/) 

---

## 🛡️ Recommendations Blueprint

✅ Upgrade EOL systems  
✅ Disable SMBv1  
✅ Deploy SIEM and IDS  
✅ Implement MFA, Password Managers  
✅ Transition to Windows 10/11 + Sandbox  
✅ Use secure protocols (SFTP, TLS, etc.)

---

## 🧠 Lessons Learned

- **System hardening** is a must, especially in finance and healthcare sectors.  
- Even non-technical users can trigger critical exploits (social engineering).  
- Real-world VAPT demands both technical depth and thorough documentation.

---

## 📫 Contact Me

📧 baratulkhan@gmail.com  
🔗 [Resume](https://docs.google.com/document/d/11HlCNrbPuuJRXANcn1F0f2KiibaG462OjIUBNbHIjJo/edit?usp=sharing)  
🌐 [LinkedIn (optional)](https://linkedin.com/in/yourprofile)  
📍 Seeking IT roles in System Administration · Network Security · Technical Support · Cybersecurity Analysis
