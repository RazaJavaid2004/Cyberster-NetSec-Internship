<div align="center">

# 🌐 CYBERSTER NetSec Internship Portfolio

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Role](https://img.shields.io/badge/Focus-Network%20Security%20Engineering-0A66C2?style=for-the-badge)](#)
[![Platform](https://img.shields.io/badge/Platform-Cisco%20Packet%20Tracer-1BA0D7?style=for-the-badge)](#)
[![Routing](https://img.shields.io/badge/Routing-OSPF%20%7C%20HSRP%20%7C%20ROAS-FF6C37?style=for-the-badge)](#)
[![Security](https://img.shields.io/badge/Security-ACLs%20%7C%20Port%20Sec%20%7C%20NAT-4EAA25?style=for-the-badge)](#)

*Transforming theoretical networking and security concepts into resilient, enterprise-grade Cisco Packet Tracer deployments.*

</div>

---

## 📌 Overview
Welcome to my Network Security engineering portfolio. This repository documents my progression through the **CYBERSTER NetSec Internship**, featuring hands-on network topologies (`.pkt`), architectural engineering reports, and verification artifacts covering multi-tier switching, dynamic routing, high availability, and perimeter security.

---

## 🏆 Awards & Certifications
Upon successfully completing the engineering modules, the ECHOBRIDGE Hackathon, and the final enterprise capstone deployment, I was awarded the **Certificate of Completion** and **Letter of Experience** by Cyberster.

<div align="center">
  <table>
    <tr>
      <td align="center"><b>Certificate of Completion</b></td>
      <td align="center"><b>Letter of Experience</b></td>
    </tr>
    <tr>
      <td><img src="awards/certificate%20of%20completion.jpg" alt="Certificate of Completion" width="420"/></td>
      <td><img src="awards/letter%20of%20experience.jpg" alt="Letter of Experience" width="420"/></td>
    </tr>
  </table>
</div>

---

## 🚀 Core Technologies & Protocols

| Domain | Technologies, Protocols & Standards Implemented |
| :--- | :--- |
| **Layer 2 Switching** | VLAN Segmentation, IEEE `802.1Q` Trunking, Spanning Tree Protocol (STP), LACP EtherChannel, Switchport Port Security |
| **Layer 3 Routing** | Static & Default Routing, Single-Area OSPF, Router-on-a-Stick (ROAS), Inter-VLAN Routing, Custom VLSM Subnetting |
| **High Availability** | HSRP (Hot Standby Router Protocol) Active/Standby Gateway Redundancy, Link Aggregation |
| **Security & Services** | Standard & Extended Access Control Lists (ACLs), NAT/PAT Overload, IOS DHCP Server Pools, SSHv2 Hardening |

---

## 🗓️ Internship Modules & Progression

### 🔹 Phase 1: Network Foundations (Weeks 1–4)
| Module | Focus Area | Key Engineering Deliverables |
| :--- | :--- | :--- |
| **Week 1** | **OSI Model Threat Analysis** | Deep dive into webpage retrieval workflows (DNS, TCP, HTTP/TLS) and theoretical threat modeling across all 7 OSI layers. |
| **Week 2** | **Physical Media Deployment** | Logical and physical infrastructure design utilizing `T568B` cabling standards, RJ45 crimping, LAN testing, and wireless module integration. |
| **Week 3** | **Layer 2 Lab Network** | Implementation of departmental VLAN segmentation, `802.1Q` trunks, MAC address table analysis, and edge Port Security to enforce Layer 2 boundaries. |
| **Week 4** | **Hierarchical Design** | Blueprinting a scalable, fault-tolerant Cisco Three-Tier Hierarchical Network Architecture (Core, Distribution, Access). |

### 🔹 Phase 2: Routing & Enterprise Architecture (Weeks 5–8)
| Module | Focus Area | Key Engineering Deliverables |
| :--- | :--- | :--- |
| **Week 5** | **Dynamic Routing** | Deployment of multi-router enterprise topologies utilizing dynamic routing protocols, wireless AP integration, and core/distribution switching. |
| **Week 6** | **TechNova Solutions Mid-Term** | Comprehensive mid-term architectural build featuring custom VLSM subnetting across departments (Finance, HR, Sales, IT), static routing to remote branches, and ACL policies. |
| **Week 8** | **Advanced Switching & Routing** | Practical execution of inter-VLAN routing concepts, sub-interface trunking, and verified inter-departmental reachability. |

### 🔹 Phase 3: Advanced Deployments & Competitions
* **⚡ ECHOBRIDGE Hackathon (`Hackathon/`):** Applied network security simulation focused on rapid topology troubleshooting, route restoration, and live threat mitigation under time constraints.
* **🏛️ Final Capstone Project (`Capstone Project/`):** End-to-end engineering of a secure, medium-sized enterprise network featuring VLSM addressing across 6 VLANs, LACP EtherChannel, HSRP gateway failover, OSPF routing, NAT/PAT translation, and strict Extended ACLs.

---

## 📂 Repository Structure
> **Note:** Folders are organized chronologically below. The `Screenshots/` directories contain **100+ verification `.png` captures** (covering CLI configurations, `show` command outputs, topology designs, and ping/PDU tests), which have been summarized in the tree to maintain readability.

```text
CYBERSTER-NetSec-Internship/
│
├── awards/
│   ├── certificate of completion.jpg
│   └── letter of experience.jpg
│
├── Week 1/
│   ├── Webpage Retrieval Workflow & OSI Model Threat Analysis.docx
│   └── Webpage Retrieval Workflow & OSI Model Threat Analysis.pdf
│
├── Week 2/
│   ├── Screenshots/          → [10 PNGs] T568B cabling, RJ45 pinouts, wireless modules & LAN testing
│   ├── Logical Infrastructure Design & Physical Media Deployment.docx
│   ├── Logical Infrastructure Design & Physical Media Deployment.pdf
│   └── week 2 - home network.pkt
│
├── Week 3/
│   ├── Screenshots/          → [26 PNGs] VLAN briefs, 802.1Q trunks, Port Security, MAC tables & PDU simulations
│   ├── Build and Validate a Layer 2 Lab Network.docx
│   ├── Build and Validate a Layer 2 Lab Network.pdf
│   └── week 3 - vlan topology.pkt
│
├── Week 4/
│   ├── Screenshots/          → [2 PNGs] Week 3 vs. Week 4 Three-Tier Hierarchical topology models
│   ├── Three-Tier Hierarchical Network Design.docx
│   ├── Three-Tier Hierarchical Network Design.pdf
│   └── week 4 - network hierarchical design.pkt
│
├── Week 5/
│   ├── Screenshots/          → [9 PNGs] Core/Aggregation router configs, Distribution switches, APs & ping tests
│   ├── Enterprise-Level Network Architecture & Dynamic Routing.docx
│   ├── Enterprise-Level Network Architecture _ Dynamic Routing.pdf
│   └── week 5 - topology.pkt
│
├── Week 6/
│   ├── Screenshots/          → [17 PNGs] VLSM subnetting calculations, Main/Remote branch routing, ACLs & pings
│   ├── TechNova Solutions Mid-Term Network Architecture.docx
│   ├── TechNova Solutions Mid-Term Network Architecture.pdf
│   └── week 6 - topology.pkt
│
├── Week 8/
│   ├── Screenshots/          → [6 PNGs] Inter-VLAN routing setup, PC IP configurations & reachability tests
│   ├── Network Routing & Switching Concepts.docx
│   ├── Network Routing & Switching Concepts.pdf
│   └── week 8 - topology.pkt
│
├── Hackathon/
│   ├── ECHOBRIDGE HACKATHON - Cyberster.pdf
│   └── hackathon.pkt
│
├── Capstone Project/
│   ├── Screenshots/          → [32 PNGs] OSPF, HSRP, LACP EtherChannel, ROAS, DHCP, NAT, SSH hardening & ACL hits
│   ├── capstone project.pkt
│   ├── Final Capstone Project Report.docx
│   └── Final Capstone Project Report.pdf
│
├── LICENSE
└── README.md
```

---

## 📑 Capstone Spotlight: Secure Enterprise Network
**Directory:** `Capstone Project/`  
Designed and deployed a resilient, multi-tier enterprise network architecture from scratch:
* **Segmentation & Scaling:** Engineered custom VLSM IP addressing across **6 dedicated VLANs** (IT, HR, Servers, Management, Guest, etc.) with `802.1Q` trunking and LACP EtherChannel bandwidth aggregation between Distribution and Access tiers.
* **Resiliency & Routing:** Configured **HSRP** across dual Edge Routers (`Edge-R1` & `Edge-R2`) for seamless default gateway failover, paired with **Single-Area OSPF** toward the ISP boundary and **Router-on-a-Stick (ROAS)** for internal routing.
* **Security & Edge Services:** Enforced **SSH-only management**, automated IP allocation via router-hosted **DHCP pools**, configured **NAT/PAT** for internet bound traffic, and deployed **Extended ACLs** to enforce strict Guest Wi-Fi/VLAN isolation and protect internal server assets.

---

## 🛠️ How to Use This Repository

1. **Clone the repository:**
   ```bash
   git clone https://github.com/RazaJavaid2004/CYBERSTER-NetSec-Internship.git
   ```
2. **Open the Network Topologies:**
   Install **Cisco Packet Tracer** (v8.2+ recommended) to open the `.pkt` files, inspect live CLI configurations, and run real-time PDU simulations.
3. **Review Architectural Reports:**
   Each directory includes comprehensive documentation in both `.pdf` (ideal for in-browser reading on GitHub) and `.docx` formats, backed by step-by-step verification screenshots in the `Screenshots/` subfolders.

---

## 🙌 Acknowledgments
This portfolio was developed during the **CYBERSTER Network Security Internship**.  
Special thanks to the Cyberster engineering mentors for designing challenging network scenarios, the ECHOBRIDGE Hackathon, and practical enterprise architecture labs.

---

## 📜 License
This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 👤 Author
**Muhammad Raza**  
🔗 [GitHub Profile](https://github.com/RazaJavaid2004)
