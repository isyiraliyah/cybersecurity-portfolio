# Google Cybersecurity Certificate — Projects

This folder contains the hands-on projects I completed as part of the **Google Cybersecurity Professional Certificate**.  
Each project demonstrates practical application of the concepts covered in the course modules.

---

## 📂 Projects
- [Controls and Compliance Checklist](Controls_and_compliance_checklist.pdf)
  Completed a security controls and compliance assessment for Botium Toys, covering frameworks such as PCI DSS, GDPR, and SOC.
- [Cybersecurity Incident Report: Network Traffic Analysis](Cybersecurity_incident_report_network_traffic_analysis.pdf)  
  Investigated DNS and ICMP traffic logs, identified that DNS queries were failing due to UDP port 53 being unreachable, and documented findings in an incident report.
- [Cybersecurity Incident Report: SYN Flood DoS Attack](Cybersecurity-Incident-Report-SYN-Flood.pdf)  
  Investigated traffic logs that revealed a **SYN flood Denial-of-Service (DoS) attack**.  
  - Logs showed repeated SYN packets from a single IP address flooding the server.
  - Errors included **gateway timeouts** and **SYN-ACK packets not received → RST responses**.  
  - Only a few successful TCP three-way handshakes were observed.  
  - Confirmed the root cause as a **SYN flood / DoS attack** disrupting normal connections.
- [Cybersecurity Incident Report: Website Malware and Redirect Attack](Security_Incident_Report_Website_Malware_and_Redirect_Attack.pdf)
  - Analyzed tcpdump logs and a sandboxed attack scenario involving a compromised website.
  - Discovered a brute force attack used to gain admin access, malicious JavaScript injection prompting users to download malware, and a redirect to a fake site (greatrecipesforme.com).
  - Recommended implementing MFA, strong password policies, and account lockouts to prevent brute force attacks.
- [Security Risk Assessment: Social Media Data Breach](Security_Risk_Assessment_SocMed_Data_Breach.pdf)
  Evaluated a breach caused by weak passwords, default admin credentials, and lack of MFA/firewall rules; proposed hardening measures to prevent future attacks.
- [Cybersecurity Incident Report: ICMP Flood DDoS Attack](Incident_report_analysis_DDoS_Attack.pdf)
  - Investigated a Distributed Denial-of-Service (DDoS) attack that used an ICMP flood to overwhelm the company’s network, exploiting an unconfigured firewall.
  - Documented a two-hour outage that prevented internal traffic from accessing critical services.
  - Applied the NIST Cybersecurity Framework (Identify, Protect, Detect, Respond, Recover) to analyze security gaps, propose mitigation strategies, and strengthen defenses.
---

⭐️ More projects will be added here as I progress through the certificate.

