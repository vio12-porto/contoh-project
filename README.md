# contoh-project
# 🚀 Make a cisco documentation project 

## 🧠 Overview

This lab demonstrates a example how to make a project.
---

## 🖥️ Topology

(Please input your topology in here)

---

## 📁 Project Structure

ospf-dhcp-project/ ├── OSPF-DHCP.pkt ← Packet Tracer project file ├── README.md ← This file └── configs/ ├── Router1.txt ├── Router2.txt └── Router3.txt

(Structure of your project)
---

## 🛠️ Technologies Used

- Cisco Packet Tracer 8.x
- OSPF (single area - area 0)
- DHCP configuration on Router2
- Loopback interfaces as Router ID
- Passive Interface for LAN ports

  (What things are use on this project)

---

## 🧪 How to Test

1. Open `OSPF-DHCP.pkt` in Packet Tracer.
2. Open any PC and verify:
   - IP is assigned via DHCP
   - You can `ping` PCs across networks
3. On routers, verify:
   - `show ip ospf neighbor`
   - `show ip route ospf`
   - `show ip dhcp binding`
  
   (Prove your project by)

---

## 📄 Configuration Notes

| Router | Key Features |
|--------|--------------|
| Router1 | OSPF with `router-id 1.1.1.1`, DHCP relay not needed |
| Router2 | **DHCP Server**, OSPF with `router-id 2.2.2.2`, passive LAN |
| Router3 | OSPF with `router-id 3.3.3.3`, receives routes via OSPF |

(If you have any requirement or a notes, write on this side)
---

✅ Project built and tested by (your name) using Cisco Packet Tracer
