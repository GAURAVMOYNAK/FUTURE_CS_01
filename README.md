# FUTURE_CS_01
TASK 1 - PERFORM A VULNERABILITY ASSESSMENT OF A  SAMPLE WEB APPLICATION
# **Vulnerability Assessment of OWASP Juice Shop**  

## **Overview**  
This repository contains a **detailed vulnerability assessment report** of the **OWASP Juice Shop** web application. The assessment was conducted using **Kali Linux, Nmap, OWASP ZAP, and Burp Suite** to identify security weaknesses and recommend mitigation strategies.  

## **Why OWASP Juice Shop?**  
OWASP Juice Shop is an **intentionally vulnerable web application** designed for penetration testing and security learning. It contains vulnerabilities such as:  
- **SQL Injection (SQLi)**  
- **Cross-Site Scripting (XSS)**  
- **Authentication and Authorization flaws**  
- **Outdated software vulnerabilities**  

This assessment serves as a **practical learning experience** for ethical hackers and security analysts.  

---

## **Files in This Repository**  

| File Name  | Description  |  
|------------|-------------|  
| `Vulnerability_Assessment_Report.md`  | Detailed assessment report in Markdown format. |  
| `screenshots/` (if applicable)  | Folder containing relevant screenshots (if added). |  

---

## **Tools Used**  

The following tools were used during the assessment:  

- **Kali Linux** – Security-focused Linux distribution.  
- **Nmap** – Network scanning and service detection.  
- **Zenmap (GUI for Nmap)** – Conducted detailed scans in GUI mode.  
- **OWASP ZAP** – Web vulnerability scanning and automated security testing.  
- **Burp Suite** – Manual penetration testing of web application vulnerabilities.  

---

## **Key Findings**  

The assessment identified **critical vulnerabilities** in the OWASP Juice Shop application, including:  

1. **SQL Injection (SQLi):** Allows unauthorized database access.  
2. **Cross-Site Scripting (XSS):** Can execute malicious scripts in user browsers.  
3. **Outdated Software:** Potential exploits due to old versions.  

For full details, refer to **[Vulnerability_Assessment_Report.md](Vulnerability_Assessment_Report.md)**.  

---

## **Recommendations & Mitigation**  

To secure web applications against these vulnerabilities, the following measures are recommended:  

### 🔹 **Preventing SQL Injection**  
✔ Use **prepared statements** and **parameterized queries**.  
✔ Implement **input validation** to block malicious inputs.  
✔ Enforce **least privilege** database access controls.  

### 🔹 **Mitigating XSS Attacks**  
✔ Use **input sanitization and output encoding**.  
✔ Implement **Content Security Policy (CSP)**.  
✔ Set **HTTPOnly and Secure flags** for cookies.  

### 🔹 **General Security Best Practices**  
✔ Regularly update **software and dependencies**.  
✔ Conduct **frequent security assessments**.  
✔ Use **role-based access control (RBAC)** to limit privileges.  

For a **detailed explanation**, see the full **[Vulnerability Assessment Report](Vulnerability_Assessment_Report.md)**.  

---

## **How to Use This Report?**  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/GAURAVMOYNAK/FUTURE_CS_01.git  
   cd FUTURE_CS_01  
   ```  
2. Open **Vulnerability_Assessment_Report.md** to view the full report.  
3. If you want to contribute, feel free to **submit a pull request**.  

---

## **Author**  
👨‍💻 **Gaurav Moynak**  
📌 **Cybersecurity & Web Security Enthusiast**  
📧 [Your Email (gaurav15moynak@gmail.com)]  
