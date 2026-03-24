# Cybersecurity Framework for Small Businesses

## Overview

Designed and implemented a practical cybersecurity framework for small business environments. The project simulates real-world attack scenarios and demonstrates how to detect, analyze, and mitigate cyber threats using open-source tools.

---

## Objectives

* Identify active hosts and network services
* Simulate cyber attacks (DoS)
* Monitor malicious network traffic
* Implement defensive security controls
* Improve overall security posture

---

## Tools Used

* Kali Linux
* Nmap
* hping3
* tcpdump
* iptables (Firewall)
* Linux system monitoring tools

---

## Methodology

### 1. Lab Setup

* Created virtual environment with:

  * Attacker machine (Kali Linux)
  * Server (Ubuntu)
  * Client system

### 2. Network Discovery

* Performed host discovery using Nmap
* Identified open ports and services

### 3. Attack Simulation

* Conducted DoS attack using hping3
* Generated high network traffic

### 4. Traffic Monitoring

* Captured packets using tcpdump
* Analyzed malicious traffic patterns

### 5. Defense Implementation

* Configured firewall rules using iptables
* Blocked malicious traffic

---

## Key Findings

* Open ports increase attack surface
* DoS attacks impact system performance
* Lack of monitoring delays detection
* Firewall effectively blocks malicious traffic

---

## Impact

* Service disruption due to attack
* High resource consumption
* Exposure of vulnerable services

---

## Mitigation

* Implement firewall rules
* Monitor network traffic continuously
* Limit exposed services
* Follow security frameworks (NIST, CIS)

---

## Key Learning

* Importance of monitoring and detection
* Real-world attack simulation
* Defensive security implementation
* Practical use of open-source tools

---

## Full Report

Detailed documentation available in: [report.docx]
