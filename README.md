# 🔐 Cisco ASA Configuration Project – CLI Mastery

Welcome! This project dives deep into configuring a **Cisco Adaptive Security Appliance (ASA)** using nothing but the **Command Line Interface (CLI)** — no GUI shortcuts here! I rolled up my sleeves and went hands-on with the essential security configurations that are the backbone of a robust enterprise firewall setup.

## 💡 What I Did

This wasn't just about punching in commands — it was about understanding how each one affects the behavior and security of the network. Here's what I got up to:

### 🔍 Part 1: ASA Exploration & Connectivity Check
- Verified connectivity across routers and PCs in a test environment.
- Explored the ASA’s version, interface setup, license, and flash file system.

### 🛠️ Part 2: Basic Setup via CLI
- Set hostname (`NETSEC-ASA`) and domain name (`netsec.com`).
- Locked down the device with an `enable` password.
- Configured **INSIDE** and **OUTSIDE** interfaces with proper security levels.
- Verified connectivity and troubleshooting with ping tests.

### 🌐 Part 3: Routing, NAT, and Firewall Policies
- Set a **default route** to reach external networks.
- Configured **PAT (Port Address Translation)** with network objects.
- Observed how firewall rules affect traffic return paths.

### 📦 Part 4: Services – DHCP, AAA & Remote Access
- Enabled the ASA as a **DHCP server** on the inside network.
- Created local AAA authentication for secure access.
- Configured **SSH** access from both internal and external hosts.

### 🧱 Part 5: DMZ Configuration and Public Server Access
- Built a DMZ using VLAN 3 and assigned it a public-facing static IP.
- Set up **Static NAT** for the DMZ web server.
- Created and applied an **ACL** to allow external HTTP access to the server.

## 🧠 Lessons Learned

Not gonna lie — setting the clock had me scratching my head for a bit 😅. But every challenge made the victory sweeter. I now understand how each ASA setting ties into real-world security implementations. This project sharpened my CLI skills and taught me to approach problems with a learner’s mindset.

---

## 📁 Skills Flexed
- Network security via CLI
- Cisco ASA configuration
- Routing, NAT, ACLs, and VLANs
- DHCP, SSH, and AAA implementation

> 🔓 Security is about understanding how systems interact, not just plugging in settings. This project let me explore that firsthand.

```
