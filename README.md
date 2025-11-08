# 🔐 Project — Setting UP A VPN

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

### Step 3 — Save and Connect
1. Click **Save**  
2. Select your VPN → Click **Connect**  
3. Once connected, confirm the status shows “Connected”

### Step 4 — Verify the Connection
Open **Command Prompt** and run:
```bash
ipconfig
