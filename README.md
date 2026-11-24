# contoh-project
# 🚀 OSPF + DHCP Network Lab (Cisco Packet Tracer)

## 🧠 Overview

This lab demonstrates a example to make a project.

- 🔁 any of routing across 3 routers
- 🆔 Loopback interfaces for stable Router IDs
- 🚫 Passive interfaces for LAN security
- 🌐 DHCP Server enabled on Router2
- 💻 PC-to-PC communication across different subnets

---

## 🖥️ Topology

[PC1]---[SW1]---[Router1]---[Router2]---[Router3]---[SW3]---[PC3] | DHCP Server


---

## 📁 Project Structure

ospf-dhcp-project/ ├── OSPF-DHCP.pkt ← Packet Tracer project file ├── README.md ← This file └── configs/ ├── Router1.txt ├── Router2.txt └── Router3.txt


---

## 🛠️ Technologies Used

- Cisco Packet Tracer 8.x
- OSPF (single area - area 0)
- DHCP configuration on Router2
- Loopback interfaces as Router ID
- Passive Interface for LAN ports

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

---

## 📄 Configuration Notes

| Router | Key Features |
|--------|--------------|
| Router1 | OSPF with `router-id 1.1.1.1`, DHCP relay not needed |
| Router2 | **DHCP Server**, OSPF with `router-id 2.2.2.2`, passive LAN |
| Router3 | OSPF with `router-id 3.3.3.3`, receives routes via OSPF |

---

✅ Project built and tested by [Shahin Akbari] using Cisco Packet Tracer
