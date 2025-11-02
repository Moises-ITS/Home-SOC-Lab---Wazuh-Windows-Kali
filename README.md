# Home-SOC-Lab---Wazuh-Windows-Kali
At home Security Operations Center (SOC) Lab, built for blue-team training and incident response practice. This lab demonstrates secure VM networking, centralised log collection with Wazuh, endpoint telemetry, and attack simulation using Kali Linux
---

## Project overview
This lab simulates a small enterprise network and enables detection, investigation, and reporting of security events.

- **SIEM:** Wazuh all-in-one (Wazuh Manager + Wazuh Indexer / OpenSearch + OpenSearch Dashboards) running on Ubuntu Server.  
- **Endpoints:** Windows Server 2019 (Domain Controller / Log source) and Windows 11 (Endpoint).  
- **Attacker:** Kali Linux (offensive tooling and simulation).  
- **Network:** VirtualBox host-only network for internal traffic + NAT for internet access.

---
