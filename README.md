# 🛡️ Sentinel-SecOps-Suite
> **Professional Cyber-Security Automation & Incident Response Framework** : A centralized command-center for Security Engineers to automate network auditing, threat detection, and system hardening using Python.

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/)
[![Security Status](https://img.shields.io/badge/Security-Audited-red.svg)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
This repository contains 9 specialized security tools:

1. Multi-Threaded Port Scanner
Description: A high-speed network reconnaissance tool.

Key Features: Uses Python threading to scan 65,535 ports in seconds. Identifies open services and potential entry points.

2. SSH Brute-Force Detector
Description: Monitors system authentication logs for attack patterns.

Key Features: Detects spikes in failed login attempts and alerts on potential brute-force attacks from specific IPs.

3. File Integrity Checker
Description: A forensic tool to monitor unauthorized file modifications.

Key Features: Uses SHA-256 hashing to compare file fingerprints and detect tampering in critical system files.

4. Error Log Grepper & Mailer
Description: Automated log monitoring and alerting system.

Key Features: Uses Regex to find "CRITICAL" or "ERROR" strings in logs and sends an automated email via SMTP.

5. Simple IDS (Log-Based)
Description: A lightweight Intrusion Detection System.

Key Features: Signature-based detection that monitors system events and alerts on suspicious activities in real-time.

6. Automated Process Killer
Description: A malware containment tool.

Key Features: Identifies unauthorized or high-CPU processes (like crypto-miners) and automatically terminates them based on a blacklist.

7. Password Strength Analyzer
Description: A tool to audit credential security.

Key Features: Evaluates passwords against entropy rules (Length, Complexity, Dictionary checks) to ensure brute-force resistance.

8. Network Connectivity Diagnostic
Description: A network health and troubleshooting utility.

Key Features: Audits DNS resolution, gateway latency, and packet loss to ensure secure and stable connections.

9. Incident Response Playbook Automator
Description: A "Trigger-Action" engine for rapid mitigation.

Key Features: Automatically executes containment steps (like network isolation) when a specific incident is detected.

🛠️ Tech Stack & Requirements
Language: Python 3.x
/Sentinel-SecOps-Suite
├── 01_Port_Scanner/        # Network Discovery
├── 02_SSH_Detector/        # Login Security
├── 03_Integrity_Checker/   # File Forensics
├── 04_Log_Mailer/          # Alerting System
├── 05_Simple_IDS/          # Intrusion Detection
├── 06_Process_Killer/      # Malware Mitigation
├── 07_Password_Analyzer/   # Credential Audit
├── 08_Net_Diagnostics/     # Network Health
└── 09_IR_Automator/        # Response Playbooks
👨‍💻 Author
Anuj Sharma Cybersecurity Enthusiast | Security Automation Specialist | Python for SecOps

Libraries Used: socket, threading, hashlib, os, re, smtplib, psutil, datetime

Platform: Linux (Ubuntu/Debian) & Windows (Admin privileges required for some tools)
