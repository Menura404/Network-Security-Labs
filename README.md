# Network-Security-Labs 

![network sec](https://github.com/user-attachments/assets/f9cae707-58d1-416e-9c2c-5adf1a27a607)

As part of my undergraduate studies in **Network Security**, I designed and implemented a secure virtual network infrastructure using **Kali Linux**. This project simulates a real-world security deployment, integrating multiple layers of protection, monitoring, and auditing techniques to defend against unauthorized access.

## Project Overview
This project focuses on designing a hardened Linux environment featuring:

- **OpenSSH server** configured with **key-based authentication**
- **Multi-Factor Authentication (MFA)** for added login security
- **Custom hardening measures** to reduce attack surfaces
- **Cowrie honeypot** deployment to track and analyze malicious activity
- **iptables firewall** to strictly filter traffic and log potential threats
- **Port scanning and vulnerability assessment** to detect and mitigate weaknesses

Although conducted in a simulated academic environment, the challenges and solutions mirror real-world scenarios faced by cybersecurity professionals.
---

## Key Features
- **Secure OpenSSH Configuration**  
  Hardened with key-based auth, disabled root login, custom ports, and protocol tuning.
- **Multi-Factor Authentication (MFA)**  
  Added a second layer of defense using tools like Google Authenticator.
- **Honeypot with Cowrie**  
  Captured and analyzed brute-force login attempts and attacker behavior.
- **Firewall Rules via iptables**  
  Crafted custom rulesets for ingress/egress filtering with robust logging.
- **Threat Detection & Logging**  
  Monitored SSH logs, honeypot logs, and firewall events to detect anomalies.
- **Vulnerability Scanning**  
  Conducted port scans and baseline audits to uncover and fix security gaps.

---

## Skills & Tools Demonstrated
- **Linux Server Hardening** (OpenSSH)
- **Multi-Factor Authentication (MFA)**
- **Honeypot Deployment & Monitoring** (Cowrie)
- **Intrusion Detection via Log Analysis**
- **iptables Configuration & Traffic Filtering**
- **Security Architecture Design**
- **Virtualized Labs & Practical Security Workflows** (Kali Linux)

---
## Architecture Diagram
<img width="1236" height="653" alt="net sec" src="https://github.com/user-attachments/assets/d3b4cdb2-8761-4fc0-b811-72eb4e7cab59" /> 

## Project Structure
- configs/ # Configuration files (OpenSSH, iptables, etc.)
- cowrie_logs/ # Sample honeypot logs & parsed analysis
- diagrams/ # Network topology and system flow diagrams
- reports/ # Vulnerability assessments & recommendations
- setup_instructions.md # Step-by-step deployment guide

--**Author : P.M. Menura Binath**--
