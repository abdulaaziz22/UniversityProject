# University Campus Network – Graduation Project 5

## Overview

This project simulates a comprehensive **university campus network** using **Cisco Packet Tracer**. It demonstrates the implementation of core Layer 2 and Layer 3 technologies to achieve reliable, scalable, and secure interdepartmental connectivity across campus zones.

## Features Implemented

- **OSPF (Open Shortest Path First)** – Dynamic routing protocol used for efficient route distribution across the network.
- **DHCP (Dynamic Host Configuration Protocol)** – Automated IP address assignment for dynamic devices.
- **VLANs (Virtual Local Area Networks)** – Logical segmentation of departments (e.g., admin, student, faculty).
- **Inter-VLAN Routing** – Enabled via Layer 3 switching or router-on-a-stick configuration.
- **HSRP (Hot Standby Router Protocol)** – Provides high availability and gateway redundancy for critical subnets.
- **Access Control Lists (ACLs)** – Enforce traffic filtering and security policies between network segments.
- **VoIP (Voice over IP)** – IP phones configured to simulate internal voice communications.
- **IP Phone Configuration** – Cisco IP Phones integrated with necessary DHCP and voice VLANs.

## Topology Highlights

- **Core Layer**: Redundant routers with OSPF and HSRP configured.
- **Distribution Layer**: VLAN-aware multilayer switches for inter-VLAN routing.
- **Access Layer**: End devices including PCs, printers, and IP phones assigned to respective VLANs.
- **VoIP Infrastructure**: IP phones receive voice-specific configurations including power via switchports, voice VLAN tagging, and DHCP option 150 for TFTP.

## How to Use

1. Open the file `University Project.pkt` using Cisco Packet Tracer (version 8.0 or higher recommended).
2. Observe the topology layout including router redundancy, VLAN segmentation, and IP phone setups.
3. Review device configurations:
   - Routers: `show run`, `show standby`, `show ip ospf neighbor`
   - Switches: `show vlan brief`, `show ip interface vlan X`, `show spanning-tree`
   - DHCP Server: Verify pools with `show ip dhcp binding`
4. Test functionality:
   - Ping across VLANs.
   - Simulate HSRP failover.
   - Check IP phone registration and communication.

## Author

**Abdulaziz Mbark**  
Cybersecurity and Networking - University Project – 2025  
