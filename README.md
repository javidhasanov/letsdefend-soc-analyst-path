# letsdefend-soc-analyst-path

# LetsDefend SOC Analyst Learning Path

This repository documents my learning journey through the LetsDefend SOC Analyst Learning Path.

The path covered core Security Operations Center (SOC) concepts, including alert investigation, log analysis, malware analysis, phishing analysis, web attack detection, SIEM operations, incident management, cyber threat intelligence, and brute-force attack detection.

In addition to completing course material, I worked on hands-on challenges and SOC investigation tickets to practice identifying suspicious activity, analyzing logs and endpoints, investigating indicators, and documenting incidents.

---

## Skills Developed

Through this learning path, I developed knowledge and practical experience in:

- SOC operations and analyst responsibilities
- SIEM alert investigation
- Log analysis
- Endpoint investigation
- Network traffic and network log analysis
- Phishing email analysis
- Malware analysis
- Dynamic malware analysis
- Malicious document analysis
- Web attack detection
- MITRE ATT&CK mapping
- Cyber Kill Chain analysis
- Incident management and response
- Cyber threat intelligence
- IOC analysis and enrichment
- VirusTotal investigations
- Splunk fundamentals
- Brute-force attack detection
- Security technologies and controls

---

# Course Summary

## 1. SOC Fundamentals

Covered the core concepts behind Security Operations Centers and the responsibilities of SOC analysts.

### Topics Covered

- Introduction to SOC
- SOC types and roles
- SOC analyst responsibilities
- SIEM and the analyst relationship
- Log management
- Endpoint Detection and Response (EDR)
- Security Orchestration, Automation and Response (SOAR)
- Threat intelligence feeds
- Common mistakes made by SOC analysts

### Key Takeaways

This course provided the foundation for understanding how a SOC operates and how security analysts use tools such as SIEM, EDR, SOAR, and threat intelligence platforms to detect, investigate, and respond to security events.

---

## 2. Cyber Kill Chain

Studied the Cyber Kill Chain model and the stages commonly involved in a cyber attack.

### Topics Covered

- Introduction to the Cyber Kill Chain
- Reconnaissance
- Weaponization
- Delivery
- Exploitation
- Installation
- Command and Control (C2)
- Actions on Objectives

### Key Takeaways

Learned how an attack can be analyzed as a sequence of stages, helping defenders identify where malicious activity occurs and where detection or response opportunities may exist.

---

## 3. MITRE ATT&CK Framework

Studied the MITRE ATT&CK framework and its structure for describing adversary behavior.

### Topics Covered

- Introduction to MITRE
- ATT&CK Matrix
- Tactics
- Techniques
- Sub-techniques
- Mitigations
- Threat groups
- Software

### Key Takeaways

Developed an understanding of how adversary behavior can be categorized using tactics and techniques and how ATT&CK can support detection, investigation, and threat analysis.

---

## 4. Phishing Email Analysis

Covered the investigation and analysis of potentially malicious emails.

### Topics Covered

- Introduction to phishing
- Information gathering
- Email headers
- Email header analysis
- Static analysis
- Dynamic analysis
- Additional analysis techniques

### Key Takeaways

Learned how to examine phishing emails, gather relevant information, analyze email headers, and investigate suspicious attachments, links, and other artifacts.

---

## 5. Detecting Web Attacks

Studied common web application attacks and methods for identifying suspicious activity.

### Topics Covered

- Web attack fundamentals
- Importance of web attack detection
- OWASP
- How web applications work
- SQL Injection
- Cross-Site Scripting (XSS)
- Command Injection
- Insecure Direct Object Reference (IDOR)
- Remote File Inclusion (RFI)
- Local File Inclusion (LFI)

### Key Takeaways

Developed familiarity with common web attack techniques and the indicators that may be present when investigating suspicious web activity.

---

## 6. Detecting Web Attacks II

Continued the study of web attacks and detection techniques.

### Topics Covered

- Open Redirection
- Directory Traversal
- Brute-force attacks
- XML External Entity (XXE) attacks

### Key Takeaways

Expanded knowledge of web-based attack techniques and how suspicious requests or patterns may indicate exploitation attempts.

---

## 7. SIEM Alert Investigation

Studied a structured process for investigating SIEM alerts.

### Topics Covered

- Introduction to SIEM alerts
- Detection
- Case creation
- Playbook initiation
- Email analysis
- Network and log analysis
- Endpoint analysis
- Investigation results

### Key Takeaways

Learned how a SOC analyst can move from an alert to an investigation by collecting evidence from multiple sources and documenting the final result.

---

## 8. Malware Analysis Fundamentals

Covered foundational concepts and approaches to malware analysis.

### Topics Covered

- Introduction to malware analysis
- Importance of malware analysis for SOC analysts
- Malware definitions and types
- Knowledge required for malware analysis
- Choosing an analysis approach
- Dynamic analysis using ANY.RUN
- Malware analysis resources

### Key Takeaways

Developed an understanding of how malware analysis supports SOC investigations and how static and dynamic analysis can be used to identify malicious behavior and extract indicators.

---

## 9. Dynamic Malware Analysis

Focused on observing malware behavior during execution in an analysis environment.

### Topics Covered

- Dynamic malware analysis fundamentals
- Importance for SOC analysts
- Required tools and software
- Virtual machine creation
- Dynamic analysis considerations
- Malware analysis examples
- Handling malware that does not immediately show activity

### Key Takeaways

Learned the importance of using controlled environments and monitoring system, process, file, and network activity to understand malware behavior.

---

## 10. Malicious Document Analysis

Covered the analysis of potentially malicious document files.

### Topics Covered

- Introduction to malicious document analysis
- Static document analysis
- Additional document analysis techniques
- Sandbox analysis

### Key Takeaways

Developed familiarity with examining suspicious documents using static analysis techniques and sandbox environments.

---

## 11. Security Solutions

Studied common security technologies used to protect and monitor enterprise environments.

### Topics Covered

- Intrusion Detection Systems (IDS)
- Intrusion Prevention Systems (IPS)
- Firewalls
- Endpoint Detection and Response (EDR)
- Antivirus software
- Sandbox solutions
- Data Loss Prevention (DLP)
- Asset management
- Web Application Firewalls (WAF)
- Load balancers
- Proxy servers
- Email security solutions

### Key Takeaways

Learned the purpose and role of common security technologies and how they contribute to detection, prevention, monitoring, and investigation.

---

## 12. Network Log Analysis

Focused on analyzing different types of network-related logs.

### Topics Covered

- Network log analysis fundamentals
- NetFlow
- Firewall logs
- VPN logs
- Proxy logs
- IDS/IPS logs
- WAF logs
- Web logs
- DNS logs

### Key Takeaways

Developed experience interpreting network-related log data and identifying potentially suspicious activity across different network security devices and services.

---

## 13. SIEM 101

Studied the basic architecture and functions of a Security Information and Event Management platform.

### Topics Covered

- SIEM fundamentals
- Log collection
- Log aggregation
- Log parsing
- Log storage
- Alerting

### Key Takeaways

Learned how security logs are collected, processed, stored, and used to generate alerts for security investigations.

---

## 14. Incident Management 101

Covered the fundamentals of managing and responding to security incidents.

### Topics Covered

- Introduction to incident management
- Incident management terminology
- Incident Management Systems (IMS)
- Case and alert naming
- Playbooks
- SOC analyst actions when an alert occurs

### Key Takeaways

Developed an understanding of how security incidents are organized, tracked, investigated, and handled using structured processes and playbooks.

---

## 15. Splunk

Studied the fundamentals of using Splunk for log collection, searching, reporting, alerting, and visualization.

### Topics Covered

- Introduction to Splunk
- Installation on Windows
- Installation on Linux
- Splunk Universal Forwarders
- Adding data
- Searching
- Reports
- Alerts
- Dashboards
- Health checks
- User management

### Key Takeaways

Developed foundational knowledge of Splunk and its role in collecting, searching, and analyzing security and operational data.

---

## 16. Cyber Threat Intelligence

Studied the fundamentals of Cyber Threat Intelligence (CTI) and its integration with SOC operations.

### Topics Covered

- Introduction to CTI
- CTI lifecycle
- Types of threat intelligence
- Attack surface determination
- Threat intelligence gathering
- Threat intelligence interpretation
- Using threat intelligence
- Threat intelligence and SOC integration

### Key Takeaways

Learned how threat intelligence can be collected, interpreted, and integrated into security operations to support detection and investigation.

---

## 17. VirusTotal for SOC Analysts

Focused on using VirusTotal as part of a SOC investigation workflow.

### Topics Covered

- File analysis
- URL analysis
- IOC searching
- Important considerations when using VirusTotal

### Key Takeaways

Developed experience using VirusTotal to investigate files, URLs, and indicators of compromise as part of security analysis and enrichment.

---

## 18. IT Security Basis for Corporates

Covered fundamental security areas used to evaluate and improve an organization's security posture.

### Topics Covered

- Asset inventory
- Backups
- Phishing prevention
- Internet browsing protection
- Patching
- Access control
- Risk analysis
- Network security
- Incident response

### Key Takeaways

Developed a broader understanding of foundational security practices that contribute to organizational resilience and preparedness for cyber incidents.

---

## 19. Detecting Brute Force Attacks

Focused on understanding and detecting brute-force attacks against different systems and services.

### Topics Covered

- Brute-force attack fundamentals
- Protocols and services targeted by brute force attacks
- Tools used in brute-force attacks
- Prevention techniques
- SSH brute-force detection
- HTTP login brute-force detection
- Windows login brute-force detection

### Key Takeaways

Learned how repeated authentication attempts can be identified and investigated across different services and operating systems.

---

# Hands-On Learning

In addition to the course material, I completed hands-on challenges and SOC investigation tickets.

- **[MSHTML-Challenge](https://github.com/javidhasanov/MSHTML-Challenge)**

---
