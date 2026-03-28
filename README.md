# SOC Brute Force Detection Lab (Wazuh SIEM)

## Objective
Demonstrate real-world SOC analyst skills including attack simulation, log analysis, and detection rule creation aligned with MITRE ATT&CK. Done by simulating a brute force attack against a Windows 11 system using Hydra from Kali Linux and detects the activity using Wazuh SIEM.

## Lab Environment
- **Attacker**: Kali Linux VM
- **Target**: Windows 11 VM
- **SIEM**: Ubuntu Wazuh server
- **PRotocol**: RDP (Port 3389)

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
