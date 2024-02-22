# Exploit CVE-2023-38646 Metabase before 0.46.6.1 (open source) and before 1.46.6.1 (Enterprise)
<p align=center><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" /></p><br>

Exploit for the Remote Code Execution (RCE) vulnerability identified in **Metabase** versions before **0.46.6.1** (open source) and **1.46.6.1** (Enterprise). The vulnerability allows attackers to execute arbitrary commands on the server at the server's privilege level, and authentication is not required for exploitation.

To execute this exploit, you will need to obtain the `setup-token`. Navigate to `/api/session/properties` on the website, where you can find the `setup-token`.

This exploit code has been developed solely for educational purposes and to enhance cybersecurity practices. **Any use for illicit purposes is entirely your own responsibility**. It is recommended to use it only in environments where explicit authorization is granted to avoid any ethical or legal violations.


**References:**
- [CVE-2023-38646](https://nvd.nist.gov/vuln/detail/CVE-2023-38646)
- [packet storm](https://packetstormsecurity.com/files/174091/Metabase-Remote-Code-Execution.html)
