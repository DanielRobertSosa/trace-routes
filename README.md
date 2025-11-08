# 🔐 Setting UP A VPN

---

## 💡 Introduction
This project demonstrates how to configure, connect, and verify a **Virtual Private Network (VPN)** connection on Windows.  
It simulates a real-world IT Support or Cloud Networking task, showing how VPNs securely connect remote devices to private networks over the internet.

---

## ⚙️ Environments & Technologies Used
- 💻 **Windows 10 / 11**
- 🌐 **VPN Protocols:** L2TP / IPSec  
- 🧠 **Command-Line Utilities:** `ipconfig`, `ping`, `tracert`
- 🔧 **Network Settings:** Windows built-in VPN Client
- ☁️ **Environment Type:** Local / Test Configuration

---

## 🧰 Operating Systems Used
- 🪟 **Windows 10**
- 🪟 **Windows 11**

---

## 🧩 Steps Included

### Step 1 — Access Network Settings
1. Open **Settings** → **Network & Internet**
2. Select **VPN** → Click **Add a VPN Connection**

### Step 2 — Configure the VPN Profile
- **VPN Provider:** Windows (built-in)  
- **Connection Name:** Choose a descriptive label (e.g., “Work VPN”)  
- **Server Name or Address:** Enter the VPN server IP or domain  
- **VPN Type:** Select `L2TP/IPSec` or `Automatic`  
- **Sign-in Info:** Username and password (if required)
  
<img width="1135" height="666" alt="step 3" src="https://github.com/user-attachments/assets/7d83df01-a37c-4336-a311-c4c5f9e6ef27" />

### Step 3 — Save and Connect
1. Click **Save**  
2. Select your VPN → Click **Connect**  
3. Once connected, confirm the status shows “Connected”

<img width="1235" height="635" alt="trace route text executed STep 4" src="https://github.com/user-attachments/assets/90788b0a-c819-4d3f-ab78-327864256b5d" />

### Step 4 — Verify the Connection
Open **Command Prompt** and run: ipconfig

 <img width="897" height="315" alt="traceouput step 5" src="https://github.com/user-attachments/assets/2fb452dd-6e1a-45d4-b371-376d0189481b" />

 ---

## 🧠 Learning Outcomes

✅ Learned how to configure and connect a VPN using Windows built-in tools  
✅ Understood how VPNs establish encrypted tunnels for secure remote access  
✅ Practiced verifying VPN connectivity using command-line utilities (ipconfig, ping, tracert)  
✅ Strengthened troubleshooting techniques for network and authentication issues  
✅ Gained foundational knowledge for Cloud, DevOps, and IT Support networking tasks  

## 🧾 Conclusion
This project provided hands-on experience configuring and verifying a **Virtual Private Network (VPN)** connection in Windows.  
I learned how to establish secure, encrypted tunnels that protect data traffic between local and remote systems.

Through this process, I practiced:
- Setting up and connecting VPNs using Windows built-in tools  
- Testing network connectivity using `ipconfig`, `ping`, and `tracert`  
- Identifying and resolving common connection or authentication issues  

These skills strengthen my foundation in **networking, cloud administration, and IT support**, reinforcing the importance of **security and encryption** in remote access environments.





