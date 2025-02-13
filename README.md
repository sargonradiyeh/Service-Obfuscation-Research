# Service Obfuscation Techniques for SSH Research

## Overview
This project investigates **service obfuscation techniques** to enhance **SSH security** by reducing its visibility to attackers. The study evaluates multiple techniques, including **port obfuscation, port knocking, Single Packet Authorization (SPA), and SSL/TLS tunneling**, analyzing their effectiveness in preventing reconnaissance and unauthorized access.

By implementing and testing these techniques in a controlled environment, this research aims to provide **practical security measures** to improve SSH resilience against attacks. The findings highlight **the importance of layered security defenses** in protecting critical services from unauthorized access.

## 🔐 **Security Techniques Explored**
- **Port Obfuscation** – Changing the SSH default port to reduce its discoverability via common scanning tools.
- **Port Knocking** – Keeping ports closed until a predefined sequence of connection attempts unlocks access.
- **Single Packet Authorization (SPA)** – Using an encrypted authentication packet to control access dynamically.
- **SSL/TLS Tunneling** – Encapsulating SSH traffic within HTTPS to mask it from detection.

## 🎥 **Demo Video**
A full demonstration of the project setup, implementation, and results is available here:
📌 **[YouTube Demo](https://youtu.be/s0wWYwjPBpQ)**

## 📂 **Project Structure**
```
/service-obfuscation-research
├── EECE655-Final_Project.pdf  # Full project report
│── README.md            # Main documentation
```

## 🛠 **Implementation & Testing Setup**
This project was tested in a **controlled lab environment** using:
- **Linux VMs** as SSH servers and penetration testing clients.
- **Nmap, Angry IP Scanner** for reconnaissance and attack simulations.
- **iptables, knockd, fwknop** for port security configurations.
- **stunnel** for SSL/TLS-based SSH tunneling.

Each technique was evaluated against common network scanning and exploitation tools, with results documenting **how effectively these methods concealed SSH services**.

## 🎯 **Security Insights**
This project is relevant for **security professionals and network administrators** aiming to:
- **Improve SSH security through obfuscation and access control**.
- **Understand attack surface reduction techniques** for critical services.
- **Test and implement advanced network security configurations**.

---
