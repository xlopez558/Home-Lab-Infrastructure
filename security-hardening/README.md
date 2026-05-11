# 🔒 Network Security & Server Hardening

## Overview
To protect my lab environment from unauthorized access and active threats, I implemented secure access controls and active monitoring across my hypervisor and management machines.

## Implementation Steps
* **Management Authentication:**
  * Generated dedicated SSH key pairs for my Linux Mint management VM to securely authenticate and push documentation to external repositories (GitHub).
* **CrowdSec Deployment (Proxmox Host):**
  * Installed and configured the CrowdSec agent directly on the Proxmox node.
  * Verified the firewall bouncer is actively protecting the hypervisor by detecting and mitigating malicious IP traffic.

## Outcome
A hardened infrastructure environment that utilizes secure authentication methods for external data transfer, while actively defending the core hypervisor against automated attacks.
