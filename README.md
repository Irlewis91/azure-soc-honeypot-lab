# Azure SOC Honeypot Lab — Microsoft Sentinel

## Overview
A home SOC lab built on Azure using a Windows VM as a honeypot,
Log Analytics Workspace for log ingestion, and Microsoft Sentinel
as the SIEM. Real-world brute-force attackers are captured, 
geo-enriched, and visualized on an attack map.

## Architecture Diagram
[Insert diagram here — see /assets/architecture.png]

## Lab Objectives
- Deploy a vulnerable VM exposed to the internet
- Forward security event logs to Log Analytics Workspace
- Ingest logs into Microsoft Sentinel
- Query failed RDP logins with KQL
- Enrich logs with geolocation data
- Build a live attack map dashboard

## Technologies Used
- Microsoft Azure (Free Subscription)
- Windows 10 VM (Honeypot)
- Log Analytics Workspace
- Microsoft Sentinel (SIEM)
- KQL (Kusto Query Language)

## Steps
1. Create Azure Free Subscription
2. Deploy Virtual Machine
3. View Raw Logs on the VM
4. Create Log Analytics Workspace
5. Connect VM to Log Analytics Workspace
6. Query Logs with KQL
7. Upload Geolocation Data
8. Inspect Enriched Logs
9. Build the Attack Map
10. Create Incidents (Bonus)

## Results / Screenshots
[Attack map screenshot here]

## References
- [Lab Video by Josh Madakor](https://youtu.be/g5JL2RIbThM)
- [Official Lab Checklist](https://docs.google.com/...)
