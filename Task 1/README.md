# 📄 Nmap Scan Report - Task 1

## 🎯 Objective
Perform a network scan using **Nmap** to identify open ports, running services, and operating system information on a target machine (`192.168.1.8`).

---

## 🧰 Tools Used
- **Tool**: Nmap 7.99  
- **Platform**: Kali Linux

---

---

## 🧪 Command Executed
```bash
nmap -sS -sV -O -oN nmap_results.txt 192.168.1.8
