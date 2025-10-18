---
title: "Lab Challenges"
layout: single
permalink: /lab-challenges/
author_profile: true
---
# Packet Tracer – WLAN Configuration Project

**Name:** ODAK IAN MWAGI  
**Date:** OCTOBER 18TH 2025  

---

## 1. Introduction
This project focuses on configuring both a **home wireless router** and an **enterprise Wireless LAN Controller (WLC)** using Cisco Packet Tracer. The main objectives are to implement **WPA2-Personal** and **WPA2-Enterprise** security, configure VLANs, DHCP scopes, and connect client devices to verify wireless connectivity.

---

## 2. Objectives
- Configure a home router with Wi-Fi for multiple devices.  
- Implement WPA2-PSK security on the home router.  
- Configure WLAN interfaces on a WLC.  
- Set up WLANs with both WPA2-PSK and WPA2-Enterprise security.  
- Connect hosts to WLANs and verify network connectivity.  

---

## 3. Configuration Summary
**Home Wireless Router:**  
- LAN IP: 192.168.6.1/27  
- DHCP Range: 192.168.6.3–192.168.6.22  
- SSID: HomeSSID  
- Security: WPA2-Personal, Password: Cisco123  

**WLC WLAN VLAN 2:**  
- Interface IP: 192.168.2.254/24  
- SSID: SSID-2  
- Security: WPA2-PSK, Password: Cisco123  

**WLC WLAN VLAN 5:**  
- Interface IP: 192.168.5.254/24  
- SSID: SSID-5  
- Security: WPA2-Enterprise, Username: userWLAN5, Password: userW5pass  

**Gateway Addresses:**  
- Home LAN: 192.168.6.1  
- VLAN 2: 192.168.2.1  
- VLAN 5: 192.168.5.1  
- Management Network: 192.168.100.1  

---

## 4. Connectivity Test
All client devices (Laptop, Tablet, Smartphone, Wireless Hosts) were successfully connected to their respective WLANs. Ping tests to the **Web Server (203.0.113.78)** and internal hosts were successful, confirming network connectivity.

---

## 5. Screenshot
![WLAN Configuration Screenshot](/assets/images/week4as2.jpg)  

---

## 6. Packet Tracer File
[Download Packet Tracer File](/assets/images/odakianWC.pka)  

---

## 7. Conclusion
This project provided hands-on experience in configuring home and enterprise wireless networks. It reinforced understanding of **wireless security, VLAN configuration, DHCP, and client connectivity verification**. The activity also highlighted the importance of proper IP addressing and network planning in WLAN setups
---
# 🧪 Lab Challenges

This page showcases some of my lab-based work and simulations, focusing on networking, cybersecurity, and system configuration. Each challenge includes the problem statement, approach, tools used, and results.

---

## 🧩 Challenge 1: Network Configuration in Packet Tracer

**Problem Statement:**  
Design and configure a small office network with three departments — Admin, Finance, and IT — ensuring connectivity and inter-departmental communication using routers, switches, and VLANs.

**Approach:**  
1. Created the network topology in Cisco Packet Tracer.  
2. Configured IP addressing and VLAN segmentation.  
3. Set up static routing and verified connectivity using `ping`.  
4. Tested end-to-end communication and optimized switch configurations.

**Tools Used:**  
- Cisco Packet Tracer  
- Command Line Interface (CLI)  
- Basic Networking Commands (`ping`, `show ip route`, `vlan database`)  

**Key Lessons Learned:**  
- Understanding VLANs and inter-VLAN routing.  
- Importance of subnetting for network efficiency.  
- Using Packet Tracer as a visualization and testing tool.

**Attachments:**  
📁 [Download Packet Tracer File (.pkt)](/assets/images/packet tracer 1.pkt)  
🖼️ ![Network Topology Screenshot](/assets/images/packet tracer 1.png)

---

## 🧠 Challenge 2: DHCP and DNS Configuration

**Problem Statement:**  
Automate IP address assignment and name resolution services for a local network using DHCP and DNS servers in Packet Tracer.

**Approach:**  
1. Configured DHCP to dynamically assign IP addresses.  
2. Set up DNS to resolve local hostnames to IPs.  
3. Connected multiple clients and tested address leasing and name resolution.  

**Tools Used:**  
- Cisco Packet Tracer  
- DHCP Server  
- DNS Server  

**Key Lessons Learned:**  
- How DHCP simplifies network management.  
- Role of DNS in network communication.  

**Attachments:**  
📁 [Download Packet Tracer File (.pkt)](/assets/images/week 4.pkt)  
🖼️ ![DHCP DNS Lab Screenshot](/assets/images/packet tracer 2.pkt.jpg)

---

### 📂 More Labs Coming Soon
Stay tuned for more Packet Tracer configurations and cybersecurity lab challenges as I continue to build and refine my technical skills.
