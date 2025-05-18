# Yug.pkt – Three-Tier Network Architecture with Wired & Wireless Setup 🌐🔌📶

Hey! 👋  
This project is a simulation of a three-tier enterprise network built in Cisco Packet Tracer. It includes a combination of wired and wireless devices, different departments, and basic server infrastructure — all designed to represent a real-world office or business network environment.

This was created as part of my internship at CodeAlpha to help me understand how large networks are designed, structured, and managed.

---

## 🏗️ Network Overview

The network follows a three-tier architecture, which is commonly used in enterprise environments for better scalability, organization, and performance:

### 🟢 Core Layer
- Two Cisco 2911 Routers
- Responsible for high-speed backbone connections
- Subnetted interfaces (e.g., 10.15.1.0/30, 10.15.13.8/30, etc.)

### 🔴 Distribution Layer
- Two Multilayer Switches (Layer 3)
- Handles VLAN routing, inter-VLAN communication, and links between core and access layers

### 🔵 Access Layer
- Three Switches (Layer 2)
- Connects all end devices including PCs, servers, and access points

---

## 💻 Devices & Segments

### 🖥️ Wired End Devices
- Multiple PCs divided across departments like Sales, Marketing, and Systems
- Connected via Access Layer switches
- Assigned to different VLANs for logical separation

### 📶 Wireless Devices
- Laptops connected through different Lightweight Access Points (LAPs) like:
  - Sales_AP
  - MR_AP
  - System_AP
- Wireless LAN Controller (WLC) handles centralized AP management

### 🧠 Server Room
- DHCP Server – assigns IP addresses
- DNS Server – resolves hostnames
- Web Server – hosts internal web services

---

## 📌 Key Features

- VLAN configuration and inter-VLAN routing
- Partial wireless integration (not fully wireless)
- Static and dynamic IP addressing via DHCP
- Centralized routing using Layer 3 switches
- Secure segmentation of network traffic

---

## 🎯 What I Learned

- How enterprise networks are structured using the three-tier model
- Basics of subnetting and inter-device communication
- How to configure wired and wireless segments in Cisco Packet Tracer
- How VLANs and routers/switches work together
- Importance of centralized management and scalable design

---

## 🛠️ How to Use This Project

1. Make sure you have Cisco Packet Tracer v8.x or above installed.
2. Download or clone this repository.
3. Open the `Yug.pkt` file inside Packet Tracer.
4. Explore device configurations, IP setup, and how data flows through the layers.


---

## 💬 Feedback or Suggestions?

This project is part of my learning journey, and I’d love to hear your thoughts or tips on how to make it better. Feel free to open an issue or connect with me.
