# Enterprise SIEM & SOC Monitoring Lab

## Project Overview

This project demonstrates the deployment and evaluation of an enterprise Security Information and Event Management (SIEM) solution using Wazuh on Microsoft Azure.

The environment was designed to simulate a real-world enterprise network where security events are centrally collected, analyzed, and monitored to detect cyber threats.

The solution includes:

- Wazuh SIEM Platform
- Azure Cloud Infrastructure
- Windows Endpoint Monitoring
- Ubuntu Server Monitoring
- Kali Linux Attack Simulation
- Network Segmentation
- File Integrity Monitoring (FIM)
- Custom Detection Rules
- MITRE ATT&CK Mapping
- Threat Detection and Alerting

---

## Architecture

The environment consists of:

- Wazuh Server
- Windows Workstation
- Ubuntu Server
- Kali Linux Attacker
- Azure Virtual Networks
- Network Security Groups
- VNet Peering

The architecture follows a segmented design to improve visibility and security monitoring across enterprise systems.

---

## Technologies Used

| Technology | Purpose |
|------------|----------|
| Wazuh | SIEM & XDR Platform |
| Microsoft Azure | Cloud Infrastructure |
| Ubuntu Linux | Wazuh Server |
| Windows Server/Workstation | Endpoint Monitoring |
| Kali Linux | Attack Simulation |
| Sysmon | Windows Event Logging |
| MITRE ATT&CK | Threat Mapping |

---

## Security Monitoring Capabilities

### Authentication Monitoring

Detects:

- Failed Logins
- Brute Force Attacks
- Unauthorized Access Attempts

### File Integrity Monitoring

Monitors:

- Critical Files
- Configuration Files
- Sensitive Data Repositories

### Threat Detection

Custom rules developed to detect:

- Authentication Abuse
- SSH Attacks
- File Tampering
- Suspicious Activity

---

## Attack Simulations

The following attack scenarios were tested:

### Windows Brute Force Attack

- Multiple authentication failures
- Detection through custom Wazuh rules

### SSH Unauthorized Access

- SSH attack simulation
- Alert generation and monitoring

### File Tampering

- Unauthorized file modification
- File Integrity Monitoring alerts

---

## MITRE ATT&CK Mapping

| Technique | Description |
|------------|------------|
| T1110 | Brute Force |
| T1078 | Valid Accounts |
| T1565.001 | Stored Data Manipulation |

---

## Skills Demonstrated

- SIEM Administration
- SOC Operations
- Threat Detection
- Incident Analysis
- Cloud Security
- Azure Administration
- Linux Administration
- Security Monitoring
- MITRE ATT&CK
- Network Segmentation

---

## Future Enhancements

- AWS Deployment
- Hybrid Cloud Monitoring
- Multi-Site Monitoring
- Active Response Automation
- Threat Intelligence Integration
- Kubernetes Monitoring

---

## Author

Mosammat Sadia Sultana

Bachelor of Information Technology (Cyber Security)

CQUniversity Australia
