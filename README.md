# SOC Lab Detection Project

## Objective
Designed and implemented a virtual Security Operations Center (SOC) lab to simulate and detect real-world attack techniques using Wazuh SIEM, Event Viewer, and Kali Linux.

## Environment
- Windows 11 endpoint
- Ubuntu Wazuh server
- Kali Linux attacker

## Attacks Simulated
- Brute force login
- Nmap reconnaissance
- PowerShell execution

## Detection Strategy
Analyzed Windows Event IDs 4624, 4625, and Event Viewer logs.

## Skills Demonstrated
- SIEM configuration
- Threat detection
- MITRE ATT&CK mapping

## Logging Tools
- Event Viewer
- Windows Event Logs
- Wazuh agents

## Lab Architecture

![SOC Lab Architecture](screenshots/soc-lab-diagram.png)

It is a Windows 11 endpoint, not Windows 10. Also tool used is Event Viewer, not Sysmon.
