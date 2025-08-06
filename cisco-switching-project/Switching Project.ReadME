# Cisco Switching Mini Project – Packet Tracer Lab

This project is a hands-on implementation of core Layer 2 switching technologies using **Cisco Packet Tracer**. It simulates a small enterprise network topology and demonstrates best practices in switch configuration, VLAN management, and link aggregation.

## 🧠 Objectives

- Implement VLAN segmentation
- Configure VTP for centralized VLAN distribution
- Aggregate links using EtherChannel (LACP/PAgP)
- Secure switch access via basic configurations
- Simulate trunking with VLAN filtering
- Apply port security measures

## 🧰 Technologies Used

- Cisco Packet Tracer
- Cisco IOS CLI (Switches: 2960-24TT)

## 🔧 Key Configurations

### ✅ VLANs
- VLAN 10: Staff
- VLAN 20: IT Department
- VLAN 30: Guests

### ✅ VTP (VLAN Trunking Protocol)
- Domain: `abcd.com`
- Mode: 
  - SW1: `server`
  - Others: `client`
- Password-protected (`cisco`)

### ✅ EtherChannel
- **PAgP** (desirable/auto)
- **LACP** (active/passive)
- Configured using `channel-group` + `port-channel` + `trunk`

### ✅ Port Security
- Max 1 MAC per port
- Sticky MAC
- Shutdown violation mode (optional for realism)

### ✅ Switch Basic Config
- `hostname` setup
- `banner motd` for legal notice
- Console and VTY password protection
- `service password-encryption`
- Disabled DNS lookup

## 🖼️ Network Topology

> 📸 See `/screenshots/SwitchingProject.png` for visual reference.

- 9 Switches connected via EtherChannel
- End-user PCs across 3 VLANs
- Trunks allowed specific VLANs only (`switchport trunk allowed vlan except 20`, etc.)

## 📁 Files Included

- `SwitchingProject.pkt` – Packet Tracer project file
- `SwitchConfigs.txt` – Sample CLI configuration per switch
- `README.md` – This documentation
- `/screenshots/SwitchingProject.png` – Topology screenshot

## 🎯 Outcomes

- Solidified understanding of Layer 2 switching concepts
- Learned to manage VLAN propagation using VTP
- Improved CLI proficiency for Cisco IOS
- Created a scalable and secure L2 network simulation

## 🚀 Next Steps

- Add Layer 3 routing and inter-VLAN communication  
- Implement DHCP, ACLs, and spanning-tree  
- Port this project into a GNS3 or EVE-NG L2/L3 hybrid lab

---

### 📎 Tags
`#Cisco` `#CCNA` `#Networking` `#PacketTracer` `#EtherChannel` `#VTP` `#VLANs` `#PortSecurity` `#SwitchingLab`

---

