# Scanning-Metasploitable

🛡️ Vulnerability Assessment of Metasploitable 2 Using Nessus
📌 Overview

This project demonstrates a vulnerability assessment conducted on a deliberately vulnerable Linux system (Metasploitable 2) using Nessus Essentials. The assessment identified critical security flaws including backdoors, remote code execution vulnerabilities, weak cryptographic configurations, and insecure authentication mechanisms.

🎯 Objectives

1. Identify critical vulnerabilities using Nessus
2. Analyze and map findings to known CVEs
3. Assess risk based on severity and exploitability
4. Provide actionable remediation strategies

🧰 Tools Used

1. Kali Linux
2. Nessus Essentials
3. Nmap
4. Metasploitable 2

🔎 Methodology

Conducted service enumeration using Nmap
Performed credentialed vulnerability scan using Nessus
Analyzed vulnerabilities based on CVSS severity
Mapped findings to known CVEs
Developed remediation strategies

🚨 Key Findings

1. UnrealIRCd Backdoor (CVE-2010-2075)
  Critical backdoor allowing remote command execution
2. Bash Shellshock RCE (CVE-2014-6271)
  Allows arbitrary command execution via environment variables
3. Weak Debian SSH Keys (CVE-2008-0166)
  Predictable SSH keys enabling unauthorized access
4. VNC Weak Authentication (CVE-1999-0506)
  Weak password vulnerability allowing unauthorized remote access
5. SSLv2/SSLv3 Enabled (CVE-2016-0800, CVE-2014-3566)
  Vulnerable to cryptographic downgrade and decryption attacks

🛠️ Remediation Summary

Remove compromised or backdoored services

Patch all outdated software and libraries

Enforce strong authentication mechanisms

Disable insecure protocols (Telnet, SSLv2/3)

Restrict service access using firewall rules

Implement secure configuration and hardening practices

📈 Key Insights

Legacy systems contain multiple critical vulnerabilities exploitable with minimal effort

Credentialed scans provide deeper visibility into system weaknesses

Misconfigurations and outdated protocols significantly increase attack surface

Proper patching and service hardening are essential for system security

🧠 Conclusion

This assessment highlights the importance of vulnerability management, secure configurations, and regular patching in maintaining system security. The findings demonstrate how multiple high-severity vulnerabilities can lead to full system compromise if left unaddressed.
