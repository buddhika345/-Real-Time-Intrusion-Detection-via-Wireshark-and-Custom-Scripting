# Real-Time Intrusion Detection via Wireshark and Custom Scripting

This project implements a simple yet effective real-time Intrusion Detection System (IDS) to detect **SYN scan attacks** using Wireshark’s CLI tool (`tshark`) and a Python script.

It continuously monitors network traffic on a specified interface and raises an alert when a suspicious number of SYN packets are detected from a single IP address—indicating a potential port scan or reconnaissance attempt.

---

## 📌 Project Features

- Real-time packet inspection using `tshark`
- Detects SYN scans by analyzing TCP flags
- Threshold-based alerting system
- Lightweight and script-based implementation
- Designed for learning, home labs, or early alerting

---

## 🛠️ Technologies Used

- Python 3
- Wireshark (`tshark`)
- Nmap (for simulation)
- Kali Linux (test environment)

---

## ⚙️ Installation & Setup

### 1. Install Dependencies

sudo apt update
sudo apt install wireshark tshark nmap python3 -y

