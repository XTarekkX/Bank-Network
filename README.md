# Enterprise Network Design and Implementation Project

This project involves designing and implementing a comprehensive enterprise network for a multi-floor office building located in Nairobi, Kenya. The network caters to various departments distributed across four floors, supporting both wired and wireless users, with dynamic IP addressing and secure routing.

---

## 🏢 Project Overview

The network supports a **four-story office building**, with each floor hosting multiple departments. Each department is isolated into its own VLAN and subnet, ensuring organized traffic flow and enhanced security.

- Each department is equipped with **both wired and wireless connectivity** to support approximately 60 users per department.
- The network enables full inter-department communication.
- Dedicated DHCP servers dynamically assign IPv4 addresses across all devices.
- HTTP and Email servers are integrated within the network to provide essential services.
- Secure remote access is configured on all routers using SSH.
- Port security is enabled on switch ports to enhance network security.

---

## 🌐 Network Design Specifications

- **Routing Protocol:** OSPF is implemented for dynamic route advertisement and network scalability.
- **IP Addressing:**  
  - The network is based on the **192.168.10.0/24** address space.
  - Subnetting is applied according to the number of hosts per department.
  - Each VLAN is assigned a unique subnet with proper subnet masks, usable IP ranges, and broadcast addresses.
- **VLAN Configuration:**  
  - Each department resides in a separate VLAN (e.g., VLAN 10, VLAN 20, VLAN 30, etc.).
- **Wireless Networks:**  
  - Wireless LANs (WLANs) are set up for each department using Cisco Access Points.
- **Port Security:**  
  - Switch ports employ sticky MAC address learning.
  - Violation action is configured to shutdown the port upon unauthorized access.
- **Basic Device Configuration:**  
  - Hostnames, console and enable passwords, banner messages, password encryption, and domain lookup disabling are configured on all devices.

---

## 🛠️ Technologies and Concepts Used

- Hierarchical network design principles.
- VLAN creation and segmentation.
- Subnetting and IP address planning.
- Inter-VLAN routing using Multilayer Switches (Switch Virtual Interfaces).
- DHCP server configuration for dynamic IP allocation.
- OSPF routing protocol setup.
- SSH configuration for secure remote device management.
- Port security implementation on switches.
- Wireless network deployment using Cisco Access Points.
- Network testing and verification.

---

## 🖥️ How to View and Use This Project

- The network is implemented using **Cisco Packet Tracer**.
- To explore the project:
  1. Open the provided project file in Cisco Packet Tracer (`.pkt`).
  2. Examine the topology, VLAN assignments, routing configuration, and wireless setups.
  3. Use the simulation mode to visualize packet flow and verify inter-department connectivity.
  4. Test DHCP address assignment and SSH access on routers.
  5. Inspect port security settings on switch interfaces.

---

## 📂 Project Files
enterprise-network/

┣ 📄 README.md ← This documentation file

┣ 📂 bank.pkt ← Cisco Packet Tracer project file

---

## 📝 Notes

- This network design is intended as a practical learning project and simulation of a real enterprise network.
- Proper subnetting and security features are emphasized to replicate real-world enterprise requirements.
- special thanks to the youtube channel gurutech for this idea to implement

---

Feel free to explore, simulate, and extend this project to deepen your understanding of enterprise network design and configuration.

