# Network Infrastructure & Engineering
A collection of enterprise-scale network designs and implementation projects.

## 🏢 Featured Project: MotorPH Corporate HQ Design
This project involved designing and validating a Layer 3 switched network for a corporate headquarters.

### Technical Specifications:
- **Topology:** Core-Access Star Topology.
- **Core Layer:** Cisco Layer 3 Switch handling Inter-VLAN routing and DHCP.
- **Access Layer:** Segmented departmental VLANs (Sales, HR, Marketing, Accounting, IT).
- **Security:** 802.1Q Trunking and Gateway redundancy.

### 🔧 Troubleshooting Log (Key Wins):
- **DHCP Resolution:** Diagnosed and fixed APIPA issues by manually provisioning VLAN databases on access switches.
- **Trunking Optimization:** Resolved rejected trunk commands by applying explicit encapsulation (`dot1q`).
- **External Routing:** Validated static routes back to the LAN for external gateway connectivity.

![Network Topology](MotorPH-Corporate-Design-Group-Project/images/Network%20Architecture%20Diagram.png)
