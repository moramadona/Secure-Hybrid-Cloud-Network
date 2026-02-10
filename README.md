# ☁️ Secure Hybrid Cloud Infrastructure Project

## 🎯 Objective
To build a secure and scalable network that simulates connecting an on-premise office to cloud-based servers using Cisco technologies.

## 🛠️ Technologies Used
* **Cisco IOS (2911 Router, 2960 Switch)**
* **VLANs & Inter-VLAN Routing (Router-on-a-Stick)**
* **Network Security (Extended Access Control Lists)**
* **NAT/PAT (Network Address Translation)**

## 🚦 Verification Tests
* **Ping Test:** VLAN 30 (Users) cannot ping VLAN 20 (Servers) due to ACL 110.
* **Web Test:** VLAN 30 can access the Web Server on Port 80.
* **Connectivity:** All VLANs can access external networks via NAT.
![Network Topology](01_Architecture/image_114353.png)
