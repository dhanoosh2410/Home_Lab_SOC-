# SOC Home Lab: Attack & Defense Simulation

## Overview
This project documents my build of a SOC home lab inspired by the public repository by xAHIINX00. The lab is designed for controlled cybersecurity learning inside isolated virtual machines.

## Scope
The lab includes:
- Attacker VM
- Windows target VM
- Splunk for monitoring
- Sysmon for Windows telemetry
- Detection-focused observation and documentation

## Objectives
- Build a small isolated lab environment
- Generate security-relevant activity in a controlled setting
- Collect and review logs in Splunk
- Document setup, observations, and troubleshooting

## Lab Components
- VirtualBox / VMware
- Kali Linux
- Windows 10 VM
- Splunk
- Sysmon

## Repository Structure
- `docs/01-lab-overview.md` — architecture and setup summary
- `docs/02-build-log.md` — step-by-step build log
- `docs/03-detection-notes.md` — monitoring and detection observations
- `docs/04-troubleshooting.md` — issues and fixes
- `assets/` — screenshots and diagrams

## Network Topology
See `assets/topology.png`

## Evidence
Screenshots and logs will be added as each stage is completed:
- VM setup
- Splunk installation
- Sysmon installation
- Log ingestion
- Detection observations

## Safety Note
This lab is intended strictly for authorized, isolated, educational use inside a private virtual lab.

## Status
Current status: In progress

## Acknowledgement
This project is based on the public learning repo:
`xAHIINX00/SOC-Home-Lab-Attack-Defense-Simulation`

## License
MIT
