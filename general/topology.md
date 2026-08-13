# Network Topology

## Overview

This project implements a multi-site enterprise network using Cisco devices.

## Site A

- R1
- SW-A1
- SW-A2
- SW-A3
- PC-A1
- PC-A2
- PC-A3

VLANs:
- VLAN 10 – SALES
- VLAN 20 – IT
- VLAN 30 – HR

## Site B

- R2
- SW-B1
- PC-B1
- PC-B2

VLANs:
- VLAN 40 – SALES
- VLAN 50 – IT

## WAN

R1 and R2 are connected through:

`10.0.0.0/30`

- R1: `10.0.0.1`
- R2: `10.0.0.2`

## Routing

- Inter-VLAN Routing using Router-on-a-Stick
- OSPF Area 0 between R1 and R2
