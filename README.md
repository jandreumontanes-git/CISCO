# 🌐 Advanced Network Design & Management

This repository contains a comprehensive collection of enterprise-level networking projects developed during my **B.Eng. in Computer Engineering** at Universitat Jaume I (UJI). The focus of these labs is the design, implementation, and troubleshooting of complex network architectures using industry-standard protocols.

## 🛠️ Technical Stack
* **Emulation/Simulation:** GNS3 (High-fidelity Cisco 7200 IOS), Cisco Packet Tracer.
* **Traffic Analysis:** Wireshark (Deep packet inspection & protocol debugging).
* **Protocols & Technologies:** OSPFv2/v3, EIGRP, BGP, IPv6, STP, VLANs, ACLs, NAT/PAT.

## 📂 Key Projects & Labs

### 1. Advanced Dynamic Routing (GNS3)
* **Multi-Area OSPF:** Implementation of hierarchical OSPF structures, including Area types (Stub, NSSA), route summarization, and cost manipulation for path optimization.
* **Enterprise EIGRP:** Advanced configuration focusing on topology tables, unequal-cost load balancing (variance), and route filtering using `distribute-lists` and `route-maps`.
* **BGP (Border Gateway Protocol):** Establishing eBGP peering between Autonomous Systems, prefix-list filtering, and path attribute manipulation.
* **IPv6 Transition:** Dual-stack implementation and OSPFv3 configuration for next-generation networking.

### 2. Infrastructure & Switching (Packet Tracer)
* **L2 Redundancy:** Configuring Spanning Tree Protocol (STP) to prevent loops and optimizing convergence with Rapid-PVST.
* **VLAN & Inter-VLAN Routing:** Logical segmentation using 802.1Q trunking and "Router-on-a-stick" architectures.
* **Network Services:** Deployment of enterprise services including DHCP, DNS, and NAT/PAT for internet edge simulation.

### 3. Network Security & Troubleshooting
* **Access Control:** Implementing Standard and Extended ACLs to enforce security policies and traffic engineering.
* **Methodological Troubleshooting:** Analyzing connectivity issues (L1-L3) and resolving configuration errors in medium-to-large scale topologies.

## 🚀 Usage
1.  **Packet Tracer:** Files with `.pkt` extension require Cisco Packet Tracer 8.0+.
2.  **GNS3:** Projects require a configured GNS3 environment with Cisco c7200 IOS images. Startup configurations are included in each lab folder.

---
*Developed as part of the EI1055: Network Design & Management course at UJI.*
