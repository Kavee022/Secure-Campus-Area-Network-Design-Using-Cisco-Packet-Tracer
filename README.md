# Secure Campus Area Network Design

A secure, scalable campus network simulation designed using **Cisco Packet Tracer**. This project models an enterprise-level network emphasizing layered security, redundancy, and segmentation.

---

## 🛠 Technologies & Features

* **Routing & Switching:** OSPF, Static & Default Routing, VLANs, Router-on-a-Stick Inter-VLAN Routing
* **High Availability:** HSRP (Hot Standby Router Protocol), LACP EtherChannel
* **Security:** Cisco ASA Firewall, ACLs, NAT, DMZ zones, SSH access for secure management
* **Wireless Infrastructure:** Cisco Wireless LAN Controller (WLC), Lightweight Access Points
* **Spanning Tree:** STP, PortFast, BPDU Guard
* **Server Integration:** Active Directory-based DHCP Server
* **Network Segmentation:** VLANs for HR, IT, Finance, Admin, Guests, and External Auditors
* **ISP Emulation:** Google Cloud Platform referenced for ISP simulation

---

## 🎯 Project Goals

* Implement secure, segmented communication between multiple departments
* Enforce role-based access control and firewall policies
* Achieve network redundancy and fault tolerance using HSRP and EtherChannel
* Provide secure Guest Wi-Fi and External Auditor access with controlled firewall rules
* Apply best practices for enterprise network design and security

---

## 🖥 Tools Used

* Cisco Packet Tracer
* Cisco IOS
* Google Cloud Platform (ISP emulation)

---

## 📁 Contents

* Network topology file (`.pkt`)
* Configuration scripts for routers, switches, and firewalls
* Documentation of VLAN IDs, IP schemes, and ACL rules

---

## 🔧 How to Use

1. Open the `.pkt` file in Cisco Packet Tracer (version 8.x or later recommended).
2. Review device configurations, especially VLANs, routing protocols, and ACLs.
3. Simulate traffic between VLANs and verify security policies.
4. Explore wireless controller setup and guest network isolation.

---

## 📚 Learning Outcomes

* Hands-on experience with enterprise routing and switching protocols
* Implementation of Cisco ASA firewall and access control lists
* Practical application of network segmentation and VLANs
* Configuring high availability and redundancy with HSRP and EtherChannel
* Understanding wireless controller and AP management

---

## License

This project is for educational purposes. Feel free to use and adapt for your own learning.
