# SIEM Lab using Splunk

## Overview
Built a home cybersecurity lab using Proxmox, Ubuntu, and Windows to simulate attacks and detect them using Splunk.

## Setup
- Proxmox virtualization
- Ubuntu (log server)
- Windows VM (target system)
- Splunk SIEM

## Data Sources
- Linux: /var/log/auth.log
- Windows: Security Event Logs (EventCode 4625, 4624)

## Simulated Attacks
- SSH brute-force login attempts
- Windows failed login attempts
- Privilege escalation using sudo

## Detection
- Failed login detection
- Brute-force detection (>5 failed attempts)
- Privilege escalation detection

## Tools Used
- Splunk
- Linux (Ubuntu)
- Windows 10
- Proxmox
