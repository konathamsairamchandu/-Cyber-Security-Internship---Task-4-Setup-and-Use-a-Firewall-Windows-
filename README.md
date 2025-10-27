# 🔥 Cyber Security Internship - Task 4: Setup and Use a Firewall (Windows)

## 🎯 Objective
Configure and test basic Windows Firewall rules to allow or block specific traffic.

---

## 🧰 Tools Used
- **Windows 11**
- **Windows Defender Firewall with Advanced Security**
- **Command Prompt**

---

## 🪜 Steps Followed

### 1️⃣ Open Windows Firewall
- Open **Control Panel → System and Security → Windows Defender Firewall → Advanced Settings**

### 2️⃣ View Current Rules
- Checked existing **Inbound Rules** to understand allowed and blocked traffic.

### 3️⃣ Block Port 23 (Telnet)
- Created a new **Inbound Rule → Port → TCP → 23 → Block the connection**
- Named it **Block Telnet Port 23**

### 4️⃣ Allow Port 22 (SSH)
- Created a new **Inbound Rule → Port → TCP → 22 → Allow the connection**
- Named it **Allow SSH Port 22**

### 5️⃣ Test Telnet Connection
Tried to connect to port 23 using Command Prompt:
```bash
telnet localhost 23
