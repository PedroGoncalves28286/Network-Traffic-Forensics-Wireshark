# Network Traffic Forensics — Malware Incident Analysis with Wireshark

**Author:** Pedro Gonçalves  
**Focus:** Digital Forensics & Incident Response (DFIR), Network Traffic Analysis, Malware Investigation

## Overview

This case study examines a supplied packet capture (PCAP) documenting a suspected Windows malware infection. It presents a structured network-forensic workflow for identifying the affected endpoint, analyzing HTTP-based delivery, examining downloaded objects, and correlating post-infection indicators.

> This repository is a historical, authorized training case study. The original PCAP was not included in this portfolio and the findings have not been independently revalidated. Indicators are for documentation, not for accessing live infrastructure.

## Tools and techniques

- Wireshark: DHCP, NBNS, LLMNR, SMB, Kerberos, and HTTP analysis
- Follow TCP Stream and HTTP Export Objects
- Kali Linux and SHA-256 sample identification
- Incident timelines, network indicators of compromise, and evidence handling

## Investigation highlights

| Item | Recorded finding |
|---|---|
| Affected Windows IP | `10.0.76.109` |
| Hostname | `BANGKOK-8AC2-PC` |
| MAC address | `78:2b:cb:d4:a5:fe` |
| Windows user | `edris.haight` |
| Reported delivery IP | `37.46.135.170` |
| Reported malware | KPOT Stealer (Rig Exploit Kit context) |
| Reported post-infection domain | `fghjkmgru34.site` |

**Evidence limitation:** The original notes contain multiple conflicting SHA-256 values. The report flags this inconsistency rather than presenting an unverified hash as definitive.

## Technical report

[Read the complete illustrated PDF report](./Network_Traffic_Forensics_Wireshark_Incident_Analysis_Pedro_Goncalves.pdf)

The PDF includes original Wireshark screenshots, a redesigned network-forensics overview diagram, investigation methods, observations, results, and limitations.

## Skills demonstrated

Network forensics · DFIR · Wireshark · PCAP analysis · HTTP traffic inspection · Endpoint attribution · Malware indicators · Evidence documentation

## Responsible use

The content is intended for defensive security education and authorized analysis. Do not attempt to contact the historical malicious domains or addresses shown in the evidence.

---
© Pedro Gonçalves — Technical portfolio.
