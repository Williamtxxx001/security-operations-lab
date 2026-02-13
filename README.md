# security-operations-lab
Simulated SOC investigation and defensive response to a web discovery attack.
images




# 🔐 Security Operations Lab – FakeBank Incident Response

## 📌 Project Overview

This project simulates a Security Operations Center (SOC) investigation involving a web discovery attack against a fictional banking institution ("FakeBank").

As the SOC Operator, I analyzed the attack, investigated the source, and implemented defensive controls to mitigate the threat.

---

## 🚨 Incident Summary

- **Attack Type:** Directory Enumeration / Web Discovery Attack
- **Risk Level:** Medium
- **Total Incidents:** 47
- **Source IP:** 32.122.195.63
- **Geolocation:** Moscow, Russia
- **Target:** Admin endpoints
- **Attack Method:** Automated scanning

The attacker attempted to enumerate sensitive admin URLs such as:

- `/admin`
- `/administrator`
- `/wp-admin`
- `/login`

---

## 🔎 Investigation Process

1. Reviewed security dashboard alerts.
2. Identified malicious source IP.
3. Analyzed attack duration and attempted URLs.
4. Reviewed threat intelligence:
   - IP Reputation: Malicious
   - Previous Attacks: 47 incidents
   - ASN: AS12345

---

## 🛡 Defensive Actions Implemented

### 1️⃣ Block Source IP
- IP Address: 32.122.195.63
- Block Duration: 72 hours

### 2️⃣ Implement Rate Limiting
- Time Window: 70 seconds
- Max Requests per Window: 60

### 3️⃣ Update WAF Rules
- Rule Description: "Block suspicious enumeration attempts"
- Purpose: Prevent similar directory scanning attacks in the future

---

## 🖼 Screenshots

### SOC Dashboard
<p align="center">
  <img src="images/Picture1.jpg" width="800"/>
</p>

### Attack Details
<p align="center">
  <img src="images/picture2.jpg" width="800"/>
</p>

### Threat Intelligence
<p align="center">
  <img src="images/picture3.jpg" width="800"/>
</p>

### Blocking Source IP
<p align="center">
  <img src="images/Picture4.jpg" width="800"/>
</p>

### WAF Rule Configuration
<p align="center">
  <img src="images/picture5.jpg" width="800"/>
</p>

### Successful Mitigation
<p align="center">
  <img src="images/picture6.jpg" width="800"/>
</p>

---

## 🎯 Skills Demonstrated

- Security Monitoring
- Incident Response
- Threat Intelligence Analysis
- Web Application Firewall (WAF) Configuration
- Rate Limiting Implementation
- Risk Assessment

---

## 🧠 Key Takeaway

This lab strengthened my understanding of defensive cybersecurity practices and SOC workflows. I gained hands-on experience identifying malicious behavior, mitigating threats, and applying layered security controls.

---

👤 William Arteaga  
Aspiring Cybersecurity & Software Professional
