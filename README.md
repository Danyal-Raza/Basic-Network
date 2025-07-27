# 🌐 Basic Network Setup in Cisco Packet Tracer

This project demonstrates a **simple but functional network topology** built using **Cisco Packet Tracer**. The goal of this setup is to showcase basic inter-network communication using **one router**, **two switches**, and **four end devices (PCs)**.

---

## 🛠️ Network Topology Overview

The network is logically divided into **two subnets**, each connected to a different switch and routed via a central router.

### 🔹 Left Side (Subnet 1):
- **Network:** `192.168.1.0/24`
- **Devices:** `PC0`, `PC1`
- **Connected to:** `Switch0`

### 🔹 Right Side (Subnet 2):
- **Network:** `192.168.2.0/24`
- **Devices:** `PC2`, `PC3`
- **Connected to:** `Switch1`

---

## ⚙️ Configuration Summary

- **Router interfaces configured** with static IP addresses for each subnet.
- **PCs assigned IPs** in their respective subnets with correct gateways.
- **Static routing (if applicable)** or **basic connectivity test** using `ping` between PCs across subnets.

---

## 📁 Files Included

- `network.pkt` – Cisco Packet Tracer file containing the complete network.
- `README.md` – Project description and configuration overview.

---

## 🎯 Learning Outcomes

- Understanding of subnetting and IP addressing
- Basic router configuration and interface setup
- Switch and host-level connectivity
- Inter-subnet communication via a router

---

## 🚀 Future Improvements

- Add DHCP configuration  
- Include a server for DNS or HTTP testing  
- Implement VLANs or NAT for extended learning  

---

## 🧠 Created By

**Syed Danyal Raza**  
Role: Cybersecurity Enthusiast | Networking Learner  
Tool: Cisco Packet Tracer  
