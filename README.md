# 🛡️ Cyber Home Lab – From Zero to Catching Attackers  

## 📌 Project Overview  
This project is a **cloud-based Home SOC (Security Operations Center)** built using Microsoft **Azure free resources**.  
The lab simulates real-world security monitoring by deploying virtual machines, enabling logging, and detecting malicious activities. 
**Goals:**  
- Build a **home lab SOC** using free cloud resources.  
- Learn how to **collect, monitor, and analyze security logs**.  
- Simulate attacks and **catch attackers in action**.
  
<img width="1099" height="616" alt="Screenshot 2025-09-08 at 7 42 21 PM" src="https://github.com/user-attachments/assets/f319b3d5-c74f-4bc0-960f-7351161c0014" />
  

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
     
    <img width="1458" height="838" alt="Screenshot 2025-08-07 at 3 40 10 PM" src="https://github.com/user-attachments/assets/5ca0d83b-51d6-40f9-9cbc-f67415e24ef6" />
 

2. **Log Collection & Analysis**  
   - Configured Log Analytics Workspace.
  <img width="1447" height="767" alt="Screenshot 2025-08-07 at 3 42 33 PM" src="https://github.com/user-attachments/assets/1ebfae6d-0472-4ebb-ac95-cfb048886ddd" />



   - Connected VM to collect logs (failed RDP/SSH, network traffic, etc.).
     
     <img width="517" height="338" alt="Screenshot 2025-08-07 at 4 00 46 PM" src="https://github.com/user-attachments/assets/a66dc63f-b894-4456-a3b0-d2a4d2a131e0" />
  
     

 

4. **Microsoft Sentinel Setup**  
   - Integrated logs into Sentinel SIEM.  
   - Created dashboards and detection rules.
  
   - <img width="1391" height="831" alt="Screenshot 2025-08-07 at 5 05 20 PM" src="https://github.com/user-attachments/assets/489ab2ca-db33-40dc-b5e7-8fed2037a531" />
     

5. **Attack Simulation & Detection**  
   - Left RDP/SSH ports open to attract attackers.  
   - Captured brute-force attempts and suspicious IPs.  
   - Analyzed logs to identify malicious activity.

     <img width="1087" height="668" alt="Screenshot 2025-08-07 at 5 32 04 PM" src="https://github.com/user-attachments/assets/47deb5a5-5dd1-41c3-a2ed-c7fcc6abf2a3" />


6. **Alerting & Insights**  
   - Configured alerts for failed logins.  
   - Visualized attacker data (IP addresses, geolocation, frequency).
  
    <img width="1406" height="659" alt="Screenshot 2025-08-07 at 5 40 26 PM" src="https://github.com/user-attachments/assets/52c94f04-7152-4125-9a9b-9edca6269ede" />
     
     
  


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
