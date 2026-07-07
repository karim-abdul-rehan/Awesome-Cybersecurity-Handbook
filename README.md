# Awesome Cybersecurity Handbooks [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
*- Karim Abdul Rehan*

<p align="center">
  <img width="450" height="580" src="/Awesome-Cybersecurity-Handbook.png">
</p>

![GitHub stars](https://img.shields.io/github/stars/karim-abdul-rehan/Awesome-Cybersecurity-Handbook?logoColor=yellow) ![GitHub forks](https://img.shields.io/github/forks/karim-abdul-rehan/Awesome-Cybersecurity-Handbook?logoColor=purple) ![GitHub watchers](https://img.shields.io/github/watchers/karim-abdul-rehan/Awesome-Cybersecurity-Handbook?logoColor=green)</br>
![GitHub commit activity (branch)](https://img.shields.io/github/commit-activity/m/karim-abdul-rehan/Awesome-Cybersecurity-Handbook) ![GitHub contributors](https://img.shields.io/github/contributors/karim-abdul-rehan/Awesome-Cybersecurity-Handbook?)

A huge chunk of my personal notes since I started playing CTFs and working as a red teamer. These are living documents and I updated or add to them relatively often.

> [!IMPORTANT]
> Please note that these documents are **only** provided for **legal purposes**. Please do **not** use the content for illigal actions.

If you like the project, give it a :star: or share it on various platforms. My goal is to create and to gather resources for people to help them on their career.

> [!NOTE]
> As always, it is pretty hard to point out every source for different tools or payloads.

Thank you for reading.

<br>

The fields of **Cybersecurity** (the broad discipline of protecting systems, networks, and data) and **Ethical Hacking** (the specific, offensive practice of testing those defenses by thinking like a cybercriminal) overlap significantly.
If you are looking at a master syllabus, a certification path (like CEH or Security+), or a textbook, the material is typically broken down into these core modules or chapters:
## 1. Fundamentals & Core Infrastructure
Before you can break a system, you have to understand how it works. This module forms the foundation of all security knowledge.
 * **The CIA Triad:** The core pillars of security—**C**onfidentiality, **I**ntegrity, and **A**vailability.
 * **Networking Architecture:** Deep dive into the OSI and TCP/IP models, routing, switching, and essential protocols (DNS, HTTP/S, SSH, FTP).
 * **Cryptography:** Symmetric vs. asymmetric encryption, hashing algorithms (SHA, MD5), Public Key Infrastructure (PKI), and digital signatures.
 * **Operating Systems (OS) Security:** Windows and Linux administration, system permissions, and mastery of the command line interface (CLI).
## 2. The Ethical Hacking Lifecycle
Ethical hacking follows a strict, legally mandated methodology to audit a target's security posture.
 * **Reconnaissance & Footprinting:** Gathering information about the target using OSINT (Open Source Intelligence), Google Dorking, and WHOIS lookups.
 * **Scanning & Enumeration:** Actively probing the network using tools like **Nmap** to find open ports, active services, and operating system types.
 * **Vulnerability Assessment:** Scanning systems with automated tools (like Nessus or OpenVAS) to isolate unpatched or weak software.
 * **Gaining Access (Exploitation):** Leveraging software vulnerabilities using exploit frameworks (like Metasploit) or exploiting weak credentials to breach a system.
 * **Maintaining Access:** Establishing persistence inside the system using backdoors or rootkits (simulating advanced threats without causing damage).
 * **Clearing Tracks:** Deleting or altering system logs to evaluate whether the organization's defensive team can detect a stealthy intruder.
 * **Reporting & Remediation:** Documenting every finding, its risk level, and step-by-step instructions on how the organization can patch the security gap.
## 3. Infrastructure & Network Hacking
This area focuses on intercepting, manipulating, and disabling network communications.
 * **Sniffing & Traffic Analysis:** Capturing and inspecting data packets traveling across a network using **Wireshark**.
 * **Man-in-the-Middle (MiTM) Attacks:** Intercepting traffic via ARP spoofing or DNS hijacking.
 * **Denial of Service (DoS & DDoS):** Flooding services to test their resilience against botnets and volumetric traffic spikes.
 * **Evading Security Controls:** Methods used to bypass Firewalls, Intrusion Detection Systems (IDS), and Honeypots.
 * **Wireless Network Security:** Exploiting weak Wi-Fi configurations, cracking WPA2/WPA3 protocols, and deploying rogue access points.
## 4. Application & System Security
This covers vulnerabilities found directly inside software code and operating systems.
 * **The OWASP Top 10:** The industry-standard list of the most critical web application vulnerabilities.
 * **Injection Attacks:** Exploiting input fields via SQL Injection (SQLi) to steal databases, or Cross-Site Scripting (XSS) to hijack user sessions.
 * **System & Endpoint Hacking:** Analyzing malware threats (Trojans, ransomware, worms), password cracking (dictionary attacks, rainbow tables), and **Privilege Escalation** (moving from a guest user to an Admin/Root user).
## 5. Human, Cloud, & Emerging Technologies
Security is only as strong as its weakest link, which is frequently the human element or misconfigured cloud spaces.
 * **Social Engineering:** Human hacking through phishing, spear-phishing, smishing (SMS phishing), vishing (voice phishing), and pretexting.
 * **Cloud Security Architecture:** Securing and auditing container environments (Docker, Kubernetes) and identity access management (IAM) flaws in platforms like AWS, Azure, and Google Cloud.
 * **IoT & Mobile Security:** Auditing smart home devices, firmware, and reverse-engineering Android/iOS mobile applications.
## 6. Defensive Operations, Forensics, & Compliance
What happens after a breach occurs, or how do organizations prevent them legally?
 * **Incident Response & Digital Forensics:** Preserving evidence, auditing log trails, and reconstructing a timeline after a security incident.
 * **SOC & Threat Intelligence:** Operating inside a Security Operations Center using SIEM tools (like Splunk) to monitor real-time security alerts.
 * **Governance, Risk, and Compliance (GRC):** Aligning an organization’s security posture with legal and industrial frameworks like GDPR, HIPAA, PCI-DSS, and ISO 27001.

## Table of Contents
|     |
| --- |
| [Fundamentals & Core Infrastructure](https://github.com/karim-abdul-rehan/Awesome-Cybersecurity-Handbook/tree/main/Fundamentals%20%26%20Core%20Infrastructure) |
| [Ethical Hacking](https://github.com/karim-abdul-rehan/Awesome-Cybersecurity-Handbook/tree/main/Ethical%20Hacking) |
| [Infrastructure & Network Hacking](https://github.com/karim-abdul-rehan/Awesome-Cybersecurity-Handbook/tree/main/Infrastructure%20%26%20Network%20Hacking) |
| [Application & System Security](https://github.com/karim-abdul-rehan/Awesome-Cybersecurity-Handbook/tree/main/Application%20%26%20System%20Security) |
| [Human, Cloud, & Emerging Technologies](https://github.com/karim-abdul-rehan/Awesome-Cybersecurity-Handbook/tree/main/Human%2C%20Cloud%2C%20%26%20Emerging%20Technologies) |
| [Defensive Operations, Forensics, & Compliance](https://github.com/karim-abdul-rehan/Awesome-Cybersecurity-Handbook/tree/main/Defensive%20Operations%2C%20Forensics%2C%20%26%20Compliance) |
| [AI, Data, & Privacy Security](https://github.com/karim-abdul-rehan/Awesome-Cybersecurity-Handbook/tree/main/AI%2C%20Data%2C%20%26%20Privacy%20Security) |
| [Advanced Topics](https://github.com/karim-abdul-rehan/Awesome-Cybersecurity-Handbook/tree/main/Advanced%20Topics) |

## **Repository Structure**
```
Awesome-Cybersecurity-Handbook
├── AI, Data, & Privacy Security
├── Advanced Topics
│   ├── Cryptography
│   ├── DevSecOps & CI \ CD Security
│   ├── Physical Security
│   └── Scripting & Automation
├── Application & System Security
│   ├── Injection Attacks
│   ├── System & Endpoint Hacking
│   └── The OWASP Top 10
├── Defensive Operations, Forensics, & Compliance
│   ├── Governance, Risk, and Compliance (GRC)
│   ├── Incident Response & Digital Forensics
│   └── SOC & Threat Intelligence
├── Ethical Hacking
│   ├── Clearing Tracks
│   ├── Gaining Access
│   ├── Maintaining Access
│   ├── Reconnaissance & Footprinting
│   ├── Reporting & Remediation
│   ├── Scanning & Enumeration
│   └── Vulnerability Assessment
├── Fundamentals & Core Infrastructure
│   ├── Networking Architecture
│   └── Operating Systems Security
├── Human, Cloud, & Emerging Technologies
│   ├── Cloud Security Architecture
│   ├── IoT & Mobile Security
│   └── Social Engineering
└── Infrastructure & Network Hacking
    ├── Denial of Service (DoS & DDoS)
    ├── Evading Security Controls
    ├── Man in the Middle (MiTM) Attacks
    ├── Sniffing & Traffic Analysis
    └── Wireless Network Security
```
