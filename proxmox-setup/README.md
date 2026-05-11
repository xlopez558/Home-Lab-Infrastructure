# 🖥️ Proxmox VE Hypervisor Deployment

## Overview
As the foundation of my home lab environment, I deployed Proxmox Virtual Environment (VE) on a bare-metal Dell OptiPlex. This setup allows for efficient resource allocation and the management of multiple Virtual Machines (VMs) and Linux Containers (LXCs) from a centralized web interface.

## Deployment Details
* **Hardware:** Dell OptiPlex
* **Hypervisor:** Proxmox VE (Debian-based)
* **Key Configurations:**
  * Executed bare-metal installation and partitioned storage for optimal VM performance.
  * Established the Linux bridge (vmbr0) for network connectivity and Web GUI access.
  * Successfully troubleshot and resolved initial kernel conflicts during the deployment phase to ensure system stability.

## Outcome
A stable, Type-1 hypervisor capable of hosting my security tools, routing software, and testing environments, mirroring a standard data center virtualization strategy.
