 **MIC CHEQUE PODCAST NETWORK – Enterprise Networking Simulation**

> *"A good network is like a good sound engineer: you don’t notice it until it fails."*  

Welcome to the **Mic Cheque Podcast Network Lab**, a fully simulated enterprise-grade infrastructure designed to showcase **advanced networking mastery**.  
This project blends **creativity, technical depth, and practical configurations** to create a realistic, secure, and scalable network.  


Engineered in **Cisco Packet Tracer**, this topology mirrors a small-scale production network for a fictional media company, complete with WAN connectivity, VLAN segmentation, routing protocols, and enterprise-level security.


 Why This Lab Stands Out

This isn’t just a Packet Tracer file; it’s a demonstration of **network engineering sophistication**:

- Configured **OSPFv2 with MD5 authentication** for secure dynamic routing.
- **WAN Serial Links** with DCE clocking to simulate ISP-grade connectivity.
- **VLANs & Trunking** for departmental segmentation.
- **Loopbacks & Subnetting** for scalable network design.
- **Passive Interfaces & Hardening** for security-first operations.
- **SSH Access, Encrypted Passwords, and Banners** for professional-grade device security.
- A **fully subnetted, point-to-point WAN design** that mirrors industry practices.


| Device        | Model       | Hostname               | Interfaces                           | Key IPs                     | Role                             |
|--------------|------------|----------------------|------------------------------------|----------------------------|---------------------------------|
| R1           | Cisco 2911  | R1-MAIN-STAGE        | Se0/3/0, Se0/3/1, Fa0/1            | 10.0.0.1, 11.0.0.1, 192.168.1.1 | Core router for Streaming Dept.|
| R2           | Cisco 2811  | R2-BACKSTAGE         | Se0/3/0, Se0/3/1                   | 11.0.0.2, 12.0.0.2          | Redundant WAN / Backstage core |
| R3           | Cisco 2811  | R3-VENDORS-BOOT      | Se0/3/0, Se0/3/1, Fa0/1            | 10.0.0.2, 12.0.0.1, 192.168.2.1 | Core router for Ticketing Dept.|
| SW3          | Cisco 2960  | SW3-STREAMING        | VLAN 10, Fa0/2                     | 192.168.1.x                 | Streaming Access Switch        |
| SW2          | Cisco 2950  | SW2-TICKETING        | VLAN 20, Fa0/2                     | 192.168.2.x                 | Ticketing Access Switch        |
| PC0          | PC          | LIVE-STREAM          | NIC                                | 192.168.1.2                 | Streaming Workstation          |
| PC1          | PC          | TICKETING-BACKSTAGE  | NIC                                | 192.168.2.2                 | Ticketing Workstation          |

---


🎯 Lab Objectives

- Showcase **multi-router OSPFv2 design** with loopbacks and secure MD5 authentication.  
- Demonstrate WAN link provisioning using **point-to-point serial connections**.  
- Apply **enterprise security best practices** on Cisco IOS devices.  
- Deliver a **highly documented, scalable, and recruiter-friendly portfolio project**.



 Features & Skills Demonstrated
| Feature                     | Purpose                                                      |
|-----------------------------|-------------------------------------------------------------|
| OSPFv2 Dynamic Routing      | Efficient routing between all subnets and WAN links         |
| MD5 Authentication          | Secure OSPF neighbor adjacency                              |
| VLAN Segmentation           | Department-based traffic separation                         |
| DCE Clock Rates             | ISP-level WAN simulation                                   |
| SSH Remote Access           | Secure remote device management                            |
| Encrypted Passwords         | Hardened device authentication                             |
| Passive Interfaces          | Minimize unnecessary routing updates                       |
| Subnetting Design           | Optimal IP address allocation                              |


Testing & Verification
| Command                        | Description                              |
|-------------------------------|------------------------------------------|
| `ping <destination>`           | Verify end-to-end connectivity           |
| `show ip route`                | Check routing table correctness         |
| `show ip ospf neighbor`        | Confirm OSPF adjacency                  |
| `show ip ospf interface`       | Inspect OSPF authentication settings    |
| `show vlan brief`              | Verify VLAN configuration               |
| `show running-config`          | Full configuration review               |


 Author - **BRADLEY GIOVANNI** 

📜 Networking Engineer | CCNA Candidate  

*"I design networks that sound as good as your favorite podcast."*

EMAIL : giovanniibradley@gmail.com

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/giovanniii293)
