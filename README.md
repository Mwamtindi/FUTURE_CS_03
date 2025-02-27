# Future Intern Internship Program - Incident Response  

## Overview  
This repository contains an **Incident Response Report** detailing the investigation of two cybersecurity incidents at **Servidae Industries** as part of the **Future Intern Internship Program**. The incidents involved a **simulated DDoS attack** and a **phishing-based workstation compromise**.  

## Incident Summary  
1. **Simulated DDoS Attack**  
   - **Type:** SYN Flood  
   - **Affected System:** Local Machine (10.0.2.3)  
   - **Analysis Tools:** Wireshark, Splunk, Kibana  
   - **Impact:** 100% packet loss, high SYN requests, potential service unavailability  

2. **Compromised Workstation**  
   - **Affected System:** Bill Smith’s workstation  
   - **Detection:** EndDefender EDR flagged suspicious remote access  
   - **Root Cause:** Phishing attack with a malicious PDF attachment  
   - **Impact:** Unauthorized access, credential theft, Remote Access Trojan (RAT) installation  

## Forensic Investigation  
- **Wireshark:** Packet analysis confirmed SYN flood patterns.  
- **Splunk:** Search queries identified malicious events and attack patterns.  
- **Kibana:** Log analysis revealed attacker’s actions and compromised assets.  

## Mitigation & Recommendations  
✅ **Firewall Rules & Rate Limiting** – To prevent SYN Flood attacks.  
✅ **Security Awareness Training** – Educate employees on phishing threats.  
✅ **Enhanced Email Filtering** – Block malicious attachments & links.  
✅ **Endpoint Security & Monitoring** – Strengthen EDR & network defenses.  

## Conclusion  
This report highlights the importance of **proactive security monitoring** and **incident response readiness**. The SOC team successfully mitigated the incidents and reinforced security measures to prevent future attacks.  

---
  
**Report Date:**  Feb 18, 2024, May 11, 2023  