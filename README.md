# CCNA
Hands-on CCNA lab implementations featuring VLANs, Inter-VLAN routing , EtherChannel, HSRP, and dynamic routing protocols, security  using Cisco Packet Tracer.

# Cisco CCNA Networking Labs

A comprehensive collection of hands-on laboratory exercises designed to master enterprise networking concepts required for the Cisco Certified Network Associate (CCNA) certification.

## 🚀 Technologies & Protocols Covered

*   **Device Management:** Initial baseline hardening, line configurations, and secure access.
*   **Layer 2 Switching:** VLAN segmentation, 802.1Q Trunking, and DTP.
*   **Inter-VLAN Routing:** Router-on-a-Stick (ROAS) and Layer 3 Switch SVIs.
*   **Link Aggregation:** EtherChannel using LACP and PAgP protocols.
*   **IP Services:** Dynamic IP assignment using DHCPv4 and SLAAC/DHCPv6.
*   **Infrastructure Security:** Layer 2 protection including Port Security and DHCP Snooping.
*   **Routing Protocols:** IPv4/IPv6 Static Routing, Default Routing, and Single-Area OSPFv2.

## 🛠️ Tools Used
*   **Cisco Packet Tracer**
*   **Cisco IOS CLI** (Command Line Interface)

## 📂 Laboratory Breakdown

### 1. Switch Basic Configurations
*   **Objective:** Establish secure administrative access and baseline settings on enterprise switches.
*   **Key Tasks:** Configured hostnames, encrypted passwords, banners, SSH access, and line console timeouts.

### 2. VLANs & Inter-VLAN Routing
*   **Objective:** Segment network broadcast domains and enable controlled inter-department routing.
*   **Key Tasks:** Created local VLANs, assigned access ports, built 802.1Q trunks, and deployed Router-on-a-Stick (ROAS).

### 3. EtherChannel Link Aggregation
*   **Objective:** Combine physical links to increase bandwidth and provide hardware redundancy.
*   **Key Tasks:** Grouped parallel switch ports into logical Port-Channels using active LACP and PAgP modes.

### 4. DHCPv4 & DHCPv6 Deployment
*   **Objective:** Automate network layer addressing configuration for endpoint devices.
*   **Key Tasks:** Configured DHCP excluded addresses, local IP pools, default gateways, and DNS server options.

### 5. Switch Security Configuration
*   **Objective:** Protect the local access layer from common network malicious exploits and unauthorized access.
*   **Key Tasks:** Implemented strict Port Security (sticky MACs/shutdown violation) and disabled unused switchports.

### 6. IPv4 & IPv6 Static and Default Routing
*   **Objective:** Establish predictable data pathways between non-directly connected networks without routing overhead.
*   **Key Tasks:** Configured next-hop static routes, exit-interface paths, and quad-zero default routes (`0.0.0.0/0` and `::/0`).

### 7. Dynamic Routing with OSPFv2
*   **Objective:** Implement a scalable, link-state dynamic routing protocol for automated path selection.
*   **Key Tasks:** Enabled OSPF processes, defined wildcard network masks, adjusted passive interfaces, and verified neighbor adjacencies.

## 📝 How to Use This Repo
1. Download and install the latest version of **Cisco Packet Tracer**.
2. Clone this repository using Git Bash:
3. Open any `.pkt` file inside the repository folders to view the active topologies and saved CLI configurations.
