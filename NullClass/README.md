🔍 Overview
This project demonstrates the practical application of CIS-CAT Pro Assessor to perform system hardening on a Windows machine in accordance with CIS Benchmarks. The goal was to elevate the system's security compliance by at least 40%, classify vulnerabilities by severity, and remediate critical misconfigurations.

👨‍💻 Project Info
Student Name: Pratik Das

Email: daspratik080@gmail.com

Course: Cyber Security

Institution: NULL CLASS

Date: 04/08/2025

Tool Used: CIS-CAT Pro Assessor

🎯 Objectives
Perform a baseline CIS-compliance scan on a Windows 10 system

Improve system compliance by remediating misconfigurations

Classify and map each issue to real-world attack vectors (e.g., MITM, Ransomware)

Apply fixes based on security best practices

Re-scan and compare pre/post-hardening compliance levels

Document the entire process with reports and screenshots

🧰 Tools & Technologies
CIS-CAT Pro Assessor

Microsoft Windows 10

Group Policy Editor (gpedit.msc)

Windows Services Configuration

Browser-based compliance reports

⚙️ Project Workflow
1. Initial Assessment
Benchmark: CIS Control Assessment Module - IG1 for Windows 10 v1.0.3

Profile: Level 1 – Member Server

Initial Compliance: ✅ 22%

Result: 83 Passed / 287 Failed / 2 Not Checked

2. Severity Classification & Threat Mapping
Each failed policy was:

Assigned a severity level (Critical, High, Medium)

Mapped to real-world threats, such as:

Credential Theft

Brute-force Attacks

Mimikatz Credential Dumping

Drive-by Downloads

3. Hardening Implementation
Remediation via Local Group Policy Editor and Services configuration

Screenshots were captured before & after each change

Policies remediated included:

Password Encryption

Password Complexity & Length

Account Lockout Policies

Disabling vulnerable protocols and services

4. Post-Hardening Reassessment
Final Compliance: ✅ 87%

Improvement: 📈 +65%

Result: 322 Passed / 48 Failed / 2 Not Checked

📊 Before vs After Comparison
Metric	Before Hardening	After Hardening
Compliance %	22%	87%
Passed Policies	83	322
Failed Policies	287	48
Not Checked	~	2

🔮 Future Recommendations
💡 Implement Local Administrator Password Solution (LAPS)

🔐 Join system to Active Directory (AD) for centralized policy control

🛡️ Deploy Endpoint Detection and Response (EDR)

🔁 Schedule regular CIS-CAT scans

🔄 Enforce Patch Management

⚙️ Use Windows Defender Application Control (WDAC)

📁 Project Assets
Initial and Final Compliance Reports (HTML)

Screenshots of Configuration Changes

Documentation of each Policy Fix

📌 Conclusion
This project showcases the effectiveness of using automated compliance tools like CIS-CAT Assessor in a real-world Windows hardening scenario. With a structured approach to risk classification, remediation, and verification, system compliance was increased from 22% to 87%, significantly reducing the attack surface.
