# Lab Overview

## Goal
To build a small SOC-style home lab for observing security telemetry in an isolated environment.

## Architecture
- Attacker VM
- Windows target VM
- Splunk instance for log review

## Main Tools
- Virtualization platform
- Kali Linux
- Windows 10
- Splunk
- Sysmon

## Intended Workflow
1. Create the virtual machines
2. Install monitoring components
3. Confirm logs are being generated and ingested
4. Review relevant events in Splunk
5. Record findings

## Isolation Controls
- Use host-only / internal networking where possible
- Do not expose the lab to the public internet unnecessarily
- Do not reuse payloads, configs, or credentials outside the lab
- Keep the environment disposable

## Deliverables
- Architecture diagram
- Setup screenshots
- Monitoring screenshots
- Detection notes
- Troubleshooting notes
