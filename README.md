# Technical Networking & Cybersecurity Portfolio
### By Alvin Chow

[cite_start]A comprehensive collection of hands-on labs focusing on enterprise routing, next-generation firewall (NGFW) deployment, cloud architecture, and layer 2 security mitigation[cite: 1, 2].

## 🛠️ Technical Skills
* **Vendors & Platforms:** Cisco (CCNP Level), Palo Alto Networks (PA-220), Fortinet (FortiGate), AWS, Kali Linux.
* **Routing Protocols:** Multi-area OSPF, eBGP, iBGP, IS-IS, EIGRP, RIP.
* **Security & Mitigation:** IPsec/SSL VPN, URL Filtering, DHCP Snooping, Dynamic ARP Inspection, BPDU Guard, Port Security].
* **Cloud Services:** AWS EC2, S3, IAM, VPC, RDS, Load Balancers, Auto Scaling.

---

## 📂 Featured Networking Labs

### 🌐 Enterprise Routing (Cisco)
* **Multi-area OSPF & IS-IS:** Designed and configured complex routing for five routers and Layer 3 switches to optimize path selection based on bandwidth and cost.
* **BGP (Exterior & Interior):** Implemented eBGP to connect multiple companies using RIP, OSPF, and EIGRP, and iBGP for consistent internal routing across branches.
* **Route Redistribution:** Successfully integrated different routing protocols by managing metric requirements to ensure full network reachability.

### 🛡️ Cybersecurity & Firewalls (Palo Alto & Fortinet)
* **Palo Alto PA-220 Deployment:** Configured SOHO environments including NAT translation, static routing, and URL filtering to isolate and secure trusted vs. untrusted zones.
***VPN Infrastructure:** Deployed **FortiGate IPsec Site-to-Site VPNs** to connect remote branch offices and **GlobalProtect/SSL VPNs** for secure remote access.
* **Layer 2 Attack Mitigation:** Simulated MAC flooding, ARP spoofing, and STP manipulation using **Kali Linux**, then mitigated them using Cisco security features like **Sticky MAC** and **BPDU Guard**.

### ☁️ Cloud Infrastructure (AWS)
* **Core Architectures:** Hands-on deployment of VPCs with public/private subnets, managed via IAM roles and protected by custom security groups.
* **High Availability & Storage:** Configured **Multi-AZ RDS** databases, Elastic Load Balancers, and Auto Scaling groups. [cite_start]Managed persistent storage using EBS volumes and S3 buckets.

---

## 🖥️ Lab Hardware
* **Workstation:** Lenovo ThinkStation P5 (Intel Xeon W5-2455X, 32GB DDR5 RAM, NVIDIA RTX A4500).
* ]**Tools:** Wireshark (Packet Analysis), PuTTY (Terminal), VMware (Virtualization).

---

## 📈 Troubleshooting & Problem Solving
I believe in learning through technical challenges. Examples from my portfolio include:
* **Redistribution Fix:** Identified missing metrics in EIGRP redistribution through Cisco forum research.
* **Firmware Management:** Resolved AP discovery issues in FortiGate by performing firmware downgrades to compatible versions.
* ]**VPN Connectivity:** Fixed IPsec tunnel failures by identifying necessary "bring up" commands within Fortinet dashboards.
