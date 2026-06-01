# SIEM Home Lab  Wazuh

A fully functional Security Information and Event Management (SIEM) 
lab built from scratch using Wazuh on Ubuntu Server.

## Objective

Build a real world SIEM environment to practice threat detection, 
log analysis, and security monitoring.

## Lab Architecture


Windows Host Machine
└── VirtualBox
    └── Ubuntu Server VM
        ├── Wazuh Manager
        ├── Wazuh Indexer
        └── Wazuh Dashboard


## Tools Used

- VirtualBox 7.2.8
- Ubuntu Server 26.04 LTS
- Wazuh 4.7.5 (SIEM Platform)

## Setup Steps

1. Installed VirtualBox on Windows host
2. Created Ubuntu Server VM (4GB RAM, 2 CPUs, 25GB disk)
3. Installed Ubuntu Server 26.04 LTS
4. Deployed Wazuh all in one installation
5. Configured port forwarding to access dashboard
6. Accessed Wazuh web dashboard via browser

## Current Status

- Wazuh Manager: Running
- Wazuh Indexer: Running
- Wazuh Dashboard: Accessible at https://127.0.0.1
- Agents: In progress

## Next Steps

- Deploy Wazuh agent on monitored VM
- Simulate attacks (failed logins, Nmap scans)
- Analyse and document security alerts
- Implement custom detection rules

## Skills Demonstrated

- Virtualisation and VM configuration
- Linux server administration
- SIEM deployment and configuration
- Network port forwarding
- Security monitoring concepts


