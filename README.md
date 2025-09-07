

# 🛡️ Cyber Home Lab – From Zero to Catching Attackers  

## 📌 Project Overview  
This project is a **cloud-based Home SOC (Security Operations Center)** built using Microsoft **Azure free resources**.  
The lab simulates real-world security monitoring by deploying virtual machines, enabling logging, and detecting malicious activities.  

**Goals:**  
- Build a **home lab SOC** using free cloud resources.  
- Learn how to **collect, monitor, and analyze security logs**.  
- Simulate attacks and **catch attackers in action**.  

---

## ⚙️ Tech Stack & Tools  
- **Azure Cloud (Free Subscription)**  
- **Windows VM / Linux VM** (honeypot for attackers)  
- **Microsoft Sentinel (SIEM)**  
- **Log Analytics Workspace**  
- **Azure Security Center / Defender**  
- **Remote Desktop / SSH**  

---

## 🔑 Key Steps Implemented  

1. **Azure Setup**  
   - Created a free Azure account.  
   - Deployed a Virtual Machine (Windows/Linux).  

2. **Log Collection & Analysis**  
   - Configured Log Analytics Workspace.  
   - Connected VM to collect logs (failed RDP/SSH, network traffic, etc.).  

3. **Microsoft Sentinel Setup**  
   - Integrated logs into Sentinel SIEM.  
   - Created dashboards and detection rules.  

4. **Attack Simulation & Detection**  
   - Left RDP/SSH ports open to attract attackers.  
   - Captured brute-force attempts and suspicious IPs.  
   - Analyzed logs to identify malicious activity.  

5. **Alerting & Insights**  
   - Configured alerts for failed logins.  
   - Visualized attacker data (IP addresses, geolocation, frequency).  

---

## 📸 Screenshots  
(Add your screenshots here for each stage)  
- Azure VM Deployment  
- Log Analytics Workspace Setup  
- Sentinel Dashboard  
- Brute-force Attack Logs  
- Attack Map Visualization  

---

## 📚 Learning Outcomes  
- Understood how to set up a **cloud-based SOC**.  
- Learned **log collection, SIEM integration, and detection rules**.  
- Gained hands-on experience in **monitoring real attacker traffic**.  
- Improved knowledge of **incident detection and response workflows**.  

---

## 🚀 Future Enhancements  
- Add more VMs for **multi-tier monitoring**.  
- Integrate **Sysmon** for advanced Windows logging.  
- Explore **Threat Hunting queries in KQL (Kusto Query Language)**.  
- Automate incident response with **Logic Apps / Playbooks**.  

---
