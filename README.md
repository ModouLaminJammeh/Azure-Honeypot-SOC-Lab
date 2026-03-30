# 🛡️ Azure Honeypot SOC Lab

## 📌 Objective
The objective of this project was to build a cloud-based honeypot environment using Microsoft Azure to simulate real-world cyber attacks and monitor them from a defender’s perspective.

Instead of relying on theoretical knowledge, I focused on deploying a vulnerable system, exposing it to the internet, and capturing live attack data. This allowed me to understand how attackers behave and how their actions are reflected in logs within a SIEM.

---

## 🧠 Skills Learned

- Hands-on experience deploying and configuring a cloud-based honeypot  
- Practical use of SIEM (Microsoft Sentinel) for threat monitoring  
- Ability to analyze real attack data such as brute-force login attempts  
- Understanding of log ingestion and query using KQL (Kusto Query Language)  
- Improved incident detection and investigation workflow  
- Better understanding of attacker behavior in exposed environments  

---

## 🧰 Tools Used

- Microsoft Azure (Virtual Machines, Networking)  
- Microsoft Sentinel (SIEM)  
- Log Analytics Workspace  
- Ubuntu Server (Honeypot target)  
- SSH for remote access and monitoring  

---

## ⚙️ Lab Setup Overview


This lab simulates a real-world SOC scenario using a cloud environment:

- A publicly exposed Ubuntu virtual machine acts as the honeypot  
- Network security settings allow inbound traffic to attract attackers  
- Logs from the VM are sent to a Log Analytics Workspace  
- Microsoft Sentinel is used to monitor, query, and analyze the logs  
- Attackers on the internet generate real telemetry (e.g., SSH brute-force attempts)  

---

## 📸 Project Steps & Screenshots

Documenting the workflow and observations:

- **Ref 1: Azure VM Deployment**  
  Creation and configuration of the Ubuntu honeypot VM  

- **Ref 2: Network Configuration**  
  Opening ports (e.g., SSH) to allow inbound attack traffic  

- **Ref 3: Log Analytics Setup**  
  Connecting the VM to Log Analytics Workspace  

- **Ref 4: Microsoft Sentinel Dashboard**  
  Viewing ingested logs and monitoring activity  

- **Ref 5: Attack Detection (Brute Force)**  
  Observing failed login attempts and suspicious IP activity  

- **Ref 6: KQL Log Analysis**  
  Querying logs to investigate attacker patterns  

---

## 🚀 Purpose

This project is part of my journey to becoming a SOC Analyst, focusing on blue team operations. By building and monitoring a live honeypot, I gain real-world experience in detecting threats, analyzing logs, and understanding how incidents are formed and investigated in a SIEM environment.
