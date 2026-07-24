# Penetration Testing Labs

> **Focus:** Penetration Testing / Offensive Security / Ethical Hacking
> **Platform:** TryHackMe and Other Authorized Security Labs
> **Purpose:** Learning, Practice, and Documentation

## Overview

This repository documents my learning journey in **Penetration Testing and Offensive Security** through hands-on labs, cybersecurity platforms, and authorized security testing environments.

The purpose of this repository is to build a strong understanding of how security vulnerabilities are discovered, assessed, and exploited in controlled environments while developing practical knowledge of common penetration testing methodologies and tools.

The knowledge gained through these exercises also helps me understand the **attacker perspective**, which is valuable for my primary interest in **SOC Analysis, Blue Team Operations, Threat Detection, and Incident Response**.

---

## Objectives

* Build a strong foundation in penetration testing.
* Understand the penetration testing lifecycle.
* Learn reconnaissance and information gathering techniques.
* Practice network and service enumeration.
* Understand vulnerability identification and assessment.
* Learn the fundamentals of exploitation.
* Understand privilege escalation concepts.
* Explore post-exploitation activities.
* Learn common offensive security tools.
* Develop an attacker mindset to improve defensive security skills.
* Document practical cybersecurity learning and methodologies.

---

## Learning Platforms

The practical learning documented in this repository is primarily based on authorized and controlled cybersecurity training environments.

* [TryHackMe](https://tryhackme.com/)
* Cybersecurity CTF platforms
* Authorized security labs
* Local virtualized environments

---

## Repository Structure

```text
Penetration-Testing-Labs/
│
├── README.md
│
├── TryHackMe/
│   │
│   ├── Pentesting-Fundamentals/
│   │   └── README.md
│   │
│   ├── Offensive-Security-Intro/
│   │   └── README.md
│   │
│   └── Web-Application-Security/
│       └── README.md
│
├── Methodologies/
│   ├── Reconnaissance.md
│   ├── Enumeration.md
│   ├── Vulnerability-Assessment.md
│   ├── Exploitation.md
│   ├── Privilege-Escalation.md
│   └── Post-Exploitation.md
│
├── Tools/
│   ├── Nmap.md
│   ├── Burp-Suite.md
│   ├── Gobuster.md 
│   └── Metasploit.md
│
└── Resources/
    └── Learning-Resources.md
```

---

## Penetration Testing Lifecycle

The learning activities in this repository follow the general penetration testing lifecycle:

```text
Authorization & Scope
        │
        ▼
Information Gathering
        │
        ▼
Reconnaissance
        │
        ▼
Enumeration
        │
        ▼
Vulnerability Identification
        │
        ▼
Exploitation
        │
        ▼
Privilege Escalation
        │
        ▼
Post-Exploitation
        │
        ▼
Documentation & Reporting
```

Each stage plays an important role in understanding how security assessments are performed in an authorized environment.

---

## Areas of Learning

### Reconnaissance

Learning how information about a target can be collected during an authorized security assessment.

Topics include:

* Passive Reconnaissance
* Active Reconnaissance
* OSINT
* Domain Information
* DNS Enumeration
* Network Discovery

---

### Enumeration

Learning how to identify exposed services, applications, and potential attack surfaces.

Topics include:

* Port Scanning
* Service Enumeration
* Version Detection
* Network Discovery
* Web Enumeration
* Directory Enumeration

---

### Vulnerability Assessment

Understanding how security weaknesses are identified and evaluated.

Topics include:

* Vulnerability Identification
* Misconfigurations
* Outdated Services
* Weak Authentication
* Common Web Vulnerabilities

---

### Exploitation

Learning the fundamentals of how identified vulnerabilities can be validated and exploited within authorized environments.

Topics include:

* Initial Access
* Exploit Concepts
* Web Exploitation
* Service Exploitation
* Payload Concepts

---

### Privilege Escalation

Understanding how attackers may attempt to increase their level of access after obtaining an initial foothold.

Topics include:

* Linux Privilege Escalation
* Windows Privilege Escalation
* Misconfigured Permissions
* Credential Discovery
* SUID and Scheduled Tasks

---

### Post-Exploitation

Learning how a compromised environment may be assessed after initial access.

Topics include:

* System Enumeration
* Credential Discovery
* Internal Reconnaissance
* Lateral Movement Concepts
* Persistence Concepts

---

## Tools

Some of the tools explored as part of my learning include:

| Tool       | Purpose                           |
| ---------- | --------------------------------- |
| Nmap       | Network and service enumeration   |
| Burp Suite | Web application security testing  |
| Gobuster   | Directory and DNS enumeration     |
| Metasploit | Exploitation framework            |
| Netcat     | Network communication and testing |
| Wireshark  | Network traffic analysis          |
| Nikto      | Web server security assessment    |

---

## Connection to SOC Analysis

Although this repository focuses on **offensive security**, the knowledge gained here supports my primary career goal of becoming a **SOC Analyst**.

Understanding attacker behavior helps me better understand what defenders need to detect.

For example:

```text
Attacker Perspective
        │
        ▼
Reconnaissance
        │
        ▼
Scanning
        │
        ▼
Exploitation
        │
        ▼
Privilege Escalation
        │
        ▼
Lateral Movement
        │
        ▼
Command & Control
        │
        ▼
        ┌───────────────────┐
        │   SOC Detection   │
        └───────────────────┘
                  │
                  ▼
          Log Analysis
                  │
                  ▼
         Alert Investigation
                  │
                  ▼
        Incident Response
```

By understanding how offensive techniques work, I can better analyze:

* Suspicious network activity
* Port scanning behavior
* Exploitation attempts
* Authentication attacks
* Privilege escalation indicators
* Lateral movement activity
* Command and Control communication

This attacker-perspective knowledge complements my learning in **SIEM, Network Traffic Analysis, Incident Response, Threat Hunting, and MITRE ATT&CK**.

---

## Documentation Approach

For each lab or room, I document:

* Overview
* Learning Objectives
* Methodology
* Topics Covered
* Tools Used
* Practical Exercises
* Skills Gained
* Key Takeaways
* Security Relevance

The goal is to document **what I learned and how I approached the problem**, rather than simply recording answers or flags.

---

## Current Learning Progress

| Area                     | Status      |
| ------------------------ | ----------- |
| Pentesting Fundamentals  | ✅ Completed |
| Reconnaissance           | 🔄 Learning |
| Enumeration              | 🔄 Learning |
| Vulnerability Assessment | 🔄 Learning |
| Web Application Security | 🔄 Learning |
| Exploitation             | 🔄 Learning |
| Privilege Escalation     | 🔄 Learning |
| Post-Exploitation        | 🔄 Learning |
| Red Team Fundamentals    | 🔄 Learning |

---

## Key Takeaways

Penetration testing provides valuable insight into how attackers identify weaknesses and compromise systems. Learning the offensive side of cybersecurity helps develop a better understanding of attack chains and the techniques that defenders need to detect.

For my career path, the objective is not to become a full-time penetration tester but to develop sufficient offensive security knowledge to strengthen my capabilities as a **SOC Analyst and Blue Team professional**.

The combination of offensive and defensive knowledge can help me better understand the relationship between **attack techniques, security telemetry, detection engineering, and incident response**.

---

## Disclaimer

This repository is created strictly for **educational and cybersecurity learning purposes**.

All practical activities documented here are performed in authorized, legal, and controlled environments such as cybersecurity training platforms and intentionally vulnerable lab systems.

**Never perform security testing against systems or networks without explicit authorization.**

