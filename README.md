# 🔐 Cyber Security Internship – Task 1

## 🛡️ Task Title:
**Scan Your Local Network for Open Ports using Nmap**

---

## 👨‍💻 Author:
**Yash Beniwal**  
Cyber Security Intern at Elevate Labs  
Date: August 4, 2025

---

## 🎯 Objective

To understand network exposure by identifying open ports on devices within the local network using Nmap.

---

## 🧰 Tools Used

- **Nmap** – for scanning live devices and open ports  
- **Wireshark** *(optional)* – for network packet analysis  
- **macOS Terminal** – to run commands  
- **GitHub CLI (`gh`)** – to securely upload this report

---

## 🔍 Key Commands Used

```bash
# Install Nmap
brew install nmap

# Discover live devices on local network
nmap -sn 192.168.1.0/24

# TCP Connect scan on specific IP
nmap -sT -Pn 192.168.1.7
