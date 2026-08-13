# CCNA-Enterprise-Multi-Site

## 📌 Description

Enterprise multi-site network project developed using Cisco Packet Tracer.

The project demonstrates VLAN segmentation, inter-VLAN routing, WAN connectivity, and dynamic routing using OSPF.

## 🎯 Objectives

- Configure VLANs
- Configure Access and Trunk ports
- Implement Inter-VLAN Routing using Router-on-a-Stick
- Configure WAN connectivity between routers
- Implement OSPF dynamic routing
- Verify network connectivity
- Perform basic network troubleshooting

## 🏢 Network Architecture

The network consists of two sites.

### Site A

- R1
- SW-A1
- SW-A2
- SW-A3
- VLAN 10
- VLAN 20
- VLAN 30

### Site B

- R2
- SW-B1
- VLAN 40
- VLAN 50

### WAN

R1 and R2 are connected through the `10.0.0.0/30` network.

## 🌐 IP Addressing

| Network | Purpose |
|---|---|
| 192.168.10.0/24 | VLAN 10 |
| 192.168.20.0/24 | VLAN 20 |
| 192.168.30.0/24 | VLAN 30 |
| 192.168.40.0/24 | VLAN 40 |
| 192.168.50.0/24 | VLAN 50 |
| 10.0.0.0/30 | WAN |

## 🛠️ Technologies

- Cisco Packet Tracer
- IPv4
- VLAN
- 802.1Q Trunk
- Router-on-a-Stick
- OSPF
- Inter-VLAN Routing
- WAN

## 📂 Project Structure

- `GENERAL/` — Network documentation
- `CONFIGURATION/` — Cisco device configurations
- `.pkt` — Cisco Packet Tracer project file

## 🔎 Verification

The network was verified using:

- `show vlan brief`
- `show interfaces trunk`
- `show ip interface brief`
- `show ip ospf neighbor`
- `show ip route`
- End-to-end ping tests

## ✅ Final Goal

Enable communication between different VLANs and between Site A and Site B using Inter-VLAN Routing and OSPF.
