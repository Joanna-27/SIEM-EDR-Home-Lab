# SIEM & EDR Home Lab

## Project Overview

This project demonstrates the implementation of a Security Information and Event Management (SIEM) and Endpoint Detection & Response (EDR) home lab using Elastic Stack and Kali Linux. The objective was to gain hands-on experience in security monitoring, threat detection, log analysis, and incident investigation by generating simulated security events and analyzing them within Kibana.

---

## Objectives

- Configure a SIEM environment using Elastic Stack.
- Deploy and manage Elastic Agent.
- Monitor endpoint activity using Elastic Defend.
- Generate and investigate security alerts.
- Understand how security events map to the MITRE ATT&CK framework.
- Develop practical experience with SOC workflows.

---

## Lab Environment

| Component | Technology |
|-----------|------------|
| Operating System | Kali Linux |
| SIEM Platform | Elastic Stack |
| Dashboard | Kibana |
| EDR | Elastic Defend |
| Agent | Elastic Agent |
| Virtualization | VirtualBox |

---

## Project Workflow

Kali Linux Endpoint

↓

Elastic Agent

↓

Elastic Cloud

↓

Kibana Dashboard

↓

Security Alerts

↓

Alert Investigation

↓

MITRE ATT&CK Analysis

---

## Detection Rules Tested

### 1. Hosts File Modified

The lab generated an alert after modifying the Linux hosts file.

This demonstrated:

- File Integrity Monitoring
- Event Detection
- Alert Generation
- Investigation Workflow

---

### 2. Interactive Shell Launched

Elastic Defend detected a suspicious interactive shell execution.

This demonstrated:

- Process Monitoring
- Endpoint Detection
- Suspicious Command Execution Detection

---

### 3. Cron Job Created

A persistence mechanism was simulated by creating a cron job.

Elastic generated an alert indicating possible persistence activity.

This demonstrated:

- Persistence Detection
- Scheduled Task Monitoring
- Linux Security Monitoring

---

## Skills Demonstrated

- SIEM Configuration
- Endpoint Detection & Response
- Threat Detection
- Security Monitoring
- Incident Investigation
- Log Analysis
- Linux Administration
- Elastic Stack
- Elastic Defend
- MITRE ATT&CK Mapping

---

## Project Report

A detailed report containing screenshots and analysis is available in this repository.

---

## Future Improvements

- Add additional attack simulations
- Configure custom detection rules
- Integrate multiple endpoints
- Create SOC investigation playbooks

---

## Author

Joanna Shefer
