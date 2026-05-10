MotorPH Layer 3 Enterprise Network Design (Cisco Packet Tracer)

This project simulates the network infrastructure of a corporate headquarters using a Core–Access Layer architecture in Cisco Packet Tracer.

📌 Project Overview

The network was designed to provide:

Departmental segmentation using VLANs
High-speed inter-VLAN routing via a Layer 3 Core Switch
Centralized DHCP services
Scalable trunk-based switching architecture
Reliable internal and external connectivity

Departments implemented:

Sales
HR
Marketing
Accounting
IT

🏗️ Network Architecture
Core–Access Design
Layer 3 Core Switch performs:
Inter-VLAN routing (SVIs)
DHCP services
Default gateway functionality
Layer 2 Access Switches connect departmental end devices
802.1Q trunk links connect Access Switches to the Core
🌐 VLAN & VLSM Implementation
Department	VLAN ID	Subnet
Sales	100	192.168.10.0/27
HR	103	192.168.10.32/28
Marketing	104	192.168.10.48/28
Accounting	106	192.168.10.64/29
IT	107	192.168.10.72/29

VLSM (Variable Length Subnet Masking) was implemented to efficiently allocate IP space according to departmental host requirements.

⚙️ Technologies & Concepts Used
VLAN Segmentation
Inter-VLAN Routing
SVIs (Switch Virtual Interfaces)
VLSM Subnetting
DHCP Configuration
802.1Q Trunking
Layer 3 Switching
Static Routing
PVST (Per-VLAN Spanning Tree)
VTP (VLAN Trunking Protocol)
🔧 Troubleshooting & Key Learning Outcomes
DHCP Troubleshooting

Resolved APIPA address issues caused by missing VLAN databases on Access Switches.

Trunking Issues

Resolved trunk encapsulation and VLAN propagation problems using explicit 802.1Q configuration.

VTP Troubleshooting

Diagnosed and resolved VTP domain mismatch issues that caused VLAN database resets and inactive VLAN ports.

Routing Validation

Verified:

Inter-VLAN communication
DHCP allocation
End-to-end connectivity
External route reachability
✅ Current Status
Fully operational Layer 3 switched network
Successful inter-VLAN routing
DHCP functioning across all VLANs
Stable VTP/VLAN propagation
External connectivity verified through simulated edge routing

Cisco Packet Tracer project created for hands-on networking practice and enterprise LAN simulation.
