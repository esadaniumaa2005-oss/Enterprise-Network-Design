# TechSolutions Ltd. - Enterprise Network Design & Simulation

A professional subnetwork architecture and static routing topology designed as part of the Pearson BTEC Level 3 Higher National curriculum in Computing. The project models a secure, scalable corporate network infrastructure connecting regional corporate branches via optimized Variable-Length Subnet Masking (VLSM).

## 🚀 Core Functionalities & Implementations
* **VLSM Address Management:** Developed a custom Class C subnetting hierarchy (`172.168.0.0/16`) to dynamically assign IP allocations across varying host requirements, starting from the largest layout block.
* **Dual-Branch Routing Topologies:** Engineered point-to-point network pathways bridging the **London Branch** (95 Hosts) and the **Brighton Branch** (34 Hosts).
* **Static Routing Configuration:** Configured predictable next-hop serial interfaces (`172.168.0.192/30`) to establish seamless, bidirectional packet forwarding parameters.
* **Fail-Safe ICMP Validation:** Successfully simulated comprehensive end-to-end device ping operations across all active subnets to ensure total data reachability.

## 📊 Subnet Engineering Scheme (VLSM Table)
* **LAN London:** `172.168.0.0/25` (Subnet Mask: `255.255.255.128`) | Gateway: `172.168.0.1`
* **LAN Brighton:** `172.168.0.128/26` (Subnet Mask: `255.255.255.192`) | Gateway: `172.168.0.129`
* **WAN Link #1:** `172.168.0.192/30` (Subnet Mask: `255.255.255.252`)

## 🛠️ Infrastructure Tools Used
* **Simulation Environment:** Cisco Packet Tracer (PC Command Line Integration)
* **Network Components:** Cisco Integrated Service Routers, Managed Layer 2 Switches, Endpoint Workstations
* **Documentation Standards:** Harvard Referencing Network Architecture

## 💡 What I Practiced
Through this practical deployment blueprint, I mastered:
1. Longest prefix match evaluation methodologies across active routing tables during multi-layered packet lookups.
2. Dynamic MAC-address discovery mechanics (`CAM Tables`) to prevent broadcast traffic storms inside multi-host switches.
3. Troubleshooting end-user routing failures and interpreting automated ICMP destination unreachable logs.

