# 🕵️ Packet Sniffer & Analyzer (Python + Wireshark)

## 📌 Project Overview
This project is a **network packet sniffer** that captures real-time traffic and extracts important data like:
- **Login attempts**
- **DNS queries**
- **HTTP traffic (unencrypted)**
- **Suspicious packets**

The program uses **Python + Scapy/PyShark** to capture packets and analyze network activity.

## 🚀 Features
✅ Live network packet capture  
✅ Filters sensitive data (unencrypted passwords, HTTP requests)  
✅ DNS request and response monitoring  
✅ Export captured data to a file  
✅ **Bonus:** Visualize network traffic with Matplotlib  

---

## ⚙️ Setup & Installation

### **🔹 Step 1: Install Dependencies**
Make sure you have **Python 3** installed. Then, install the required libraries:

```bash
pip install scapy pyshark matplotlib
