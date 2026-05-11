# 🛡️ OPNsense Virtual Firewall & Network Segmentation

## Overview
To establish secure routing and isolate my lab services from standard local traffic, I deployed OPNsense as a virtualized firewall within my Proxmox hypervisor. This project demonstrates core networking concepts, including logical segmentation, subnetting, and advanced firewall rule management.

## Implementation Steps
* **Virtualization & Routing:**
  * Deployed OPNsense as a VM, managing virtualized interfaces and disabling the default Proxmox firewall on specific bridges to prevent routing conflicts.
* **VLAN Segmentation & DMZ:**
  * Configured distinct Virtual LANs (VLANs) to separate traffic into dedicated broadcast domains.
  * Established a dedicated **Management VLAN** for infrastructure control and an isolated **DMZ** for web-facing services.
* **Access Control & Security Rules:**
  * Implemented strict RFC1918 firewall rules to block unauthorized cross-talk between subnets.
  * Utilized a Linux Mint VM as a secure "jump box," ensuring administrative access to the infrastructure is tightly controlled and isolated from general network traffic.

## Outcome
A professional, logically segmented network topology that provides granular control over traffic flow, effectively mimicking enterprise-level zero-trust architectures.
