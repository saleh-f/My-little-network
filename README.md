# Advanced IT Networking and Cybersecurity Project

## Overview

This project encompasses the design, configuration, and management of an enterprise-level network environment using Cisco Packet Tracer. The main focus areas include advanced networking, VLAN segmentation, DHCP and DNS setup, server management, wireless network deployment, IoT integration, and secure remote access.

---

## Project Summary

The work involved hands-on configuration and simulation of real-world network scenarios, covering the following key areas:

### Networking Fundamentals
- Applied core networking concepts such as the OSI model, IP addressing, subnetting, and VLANs.
- Configured Layer 2 switches and routers for VLAN segmentation and inter-VLAN routing.

### VLAN and Inter-VLAN Routing
- Created multiple VLANs to segment different departments: Sales (VLAN 10), IT (VLAN 11), HR (VLAN 12), Guests (VLAN 100 & 101), and IoT Devices (VLAN 200).
- Configured trunk ports for VLAN traffic between switches and routers.
- Implemented ACLs to control communication between VLANs, maintaining network security and segmentation.

### DHCP and DNS Configuration
- Set up DHCP pools for each VLAN to dynamically assign IP addresses.
- Configured a DNS server and integrated DHCP options to distribute DNS server IPs to clients across VLANs.

### Server Management
- Installed and configured servers for:
  - Email (Static IP: 192.168.1.3)
  - FTP (Static IP: 192.168.1.4)
  - HTTP hosting multiple websites
  - IoT Management (Static IP: 192.168.200.10) for device registration and control

### Wireless Network Deployment
- Deployed multiple Access Points connected to specific VLANs for Sales, IT, and HR departments.
- Created guest wireless networks with separate VLANs and SSIDs to isolate guest traffic.
- Applied ACLs to prevent guest network access to internal resources.

### IoT Network Integration
- Established a dedicated VLAN (200) for IoT devices to isolate them from core enterprise VLANs.
- Connected IoT devices via a Home Gateway and registered them on an IoT management server.
- Enforced security policies restricting IoT device access to internal networks.

### Secure Remote Access Using SSH
- Configured SSH on routers for encrypted remote management.
- Created local user accounts with privilege levels.
- Disabled Telnet to enhance security.
- Applied ACLs restricting SSH access to trusted IP ranges.

---

## Technologies and Tools Used

- **Cisco Packet Tracer** for network simulation and device configuration.
- **Cisco routers and switches** (Layer 2 switching and Layer 3 routing).
- Simulated servers running DNS, DHCP, FTP, HTTP, and IoT management services.
- Network security fundamentals including ACLs and SSH.

---

## Usage and Applications

This project can be used as a reference for:

- Designing VLAN-segmented networks with inter-VLAN routing.
- Implementing DHCP and DNS in multi-VLAN environments.
- Deploying and managing basic network services.
- Integrating wireless networks with VLANs.
- Introducing and securing IoT devices within an enterprise network.
- Setting up secure remote device management.

---

## Future Improvements

- Adding network monitoring with Syslog and SNMP.
- Implementing firewall solutions and advanced ACL policies.
- Configuring Quality of Service (QoS) for traffic management.
- Exploring cloud integration for hybrid networking.

---

## Contact

Feel free to reach out for further discussion or collaboration.

---

*Thank you for reviewing this project.*

