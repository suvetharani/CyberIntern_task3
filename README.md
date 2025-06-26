# 🔍 Vulnerability Scan on Personal Computer

## 🧾 Overview

This project demonstrates a basic vulnerability assessment of a personal computer using a free vulnerability scanner(Nessus). The goal is to identify potential security weaknesses, analyze the scan report, and document the most critical issues with their possible fixes.

---

## 🎯 Objective

To identify potential vulnerabilities on a personal computer using a free vulnerability scanning tool, analyze the scan results, and document the most critical security issues along with appropriate mitigation strategies to enhance system security.

---

## 🛠 Tools Used

- [Nessus Essentials](https://www.tenable.com/products/nessus/nessus-essentials)

---

## 🧪 Procedure

1. **Installation**  
   Installed Nessus Essentials / OpenVAS on the local machine.

2. **Setup Scan Target**  
   Configured the target IP as  `192.168.56.1` (local), and `123.123.123.123` (external test host).

3. **Launch Full Scan**  
   Started a full vulnerability scan, which took approximately 30–60 minutes.

4. **Analyze Results**  
   Reviewed the scan report focusing on *critical* and *high-severity* vulnerabilities.

5. **Mitigation Research**  
   Researched recommended solutions for each vulnerability using CVE references.

6. **Documentation**  
   Reports and screenshots are saved in the `/screenshots` directories.

---

## 📄 Deliverables

- ✅ HTML report for external host `123.123.123.123`
- ✅ CSV report for local host `192.168.56.1`
- ✅ Screenshots of Scan Results
- ✅ Summary of Critical Vulnerabilities
- ✅ Suggested Fixes / Mitigations

---

## 📸 Screenshots

> Screenshots of the scan interface, summary, and critical vulnerabilities can be found in the `/screenshots` directory.


---

## ✅ Conclusion

The vulnerability scan successfully identified multiple security risks on the system. A separate external IP (`123.123.123.123`) was also scanned to explore additional real-world vulnerabilities. The results emphasize the importance of regular vulnerability scanning and keeping systems updated to maintain strong security.

---

## 🔐 Disclaimer

This project was conducted for **educational purposes only** on personal and authorized systems. Unauthorized scanning or exploitation of systems is illegal and unethical.

