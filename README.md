# Wireshark-task

# Task 5 - Capture and Analyze Network Traffic Using Wireshark

## ✅ Objective
Capture live packets and identify HTTP, DNS, and TCP protocols using Wireshark.

---

## 🧰 Tools Used
- *Wireshark 4.4.4*
- *Kali Linux VM (VirtualBox)*
- *Browser* for accessing HTTP sites (like neverssl.com)
- *Ping & Nslookup* commands

---

## 🔍 Protocols Captured

### 1. *DNS (Domain Name System)*
- Used for resolving domain names.
- Observed standard queries for domains like google.com.
- Example packet:  
  Standard query A google.com → Response: 142.250.77.78

### 2. *TCP (Transmission Control Protocol)*
- Used for establishing reliable connections.
- Observed 3-way handshake: SYN → SYN-ACK → ACK.
- Multiple TCP segments between source 10.0.2.15 and 34.223.124.45

### 3. *HTTP (Hypertext Transfer Protocol)*
- Captured from visiting http://neverssl.com.
- Example GET request:****
