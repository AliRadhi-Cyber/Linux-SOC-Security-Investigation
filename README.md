# Linux SOC Security Investigation

## Project Overview
A hands-on cybersecurity investigation focused on Linux system hardening, authentication monitoring, incident triage, and forensic evidence preservation.

**Incident ID:** LINUX-001

## Tools and Technologies
- Ubuntu 24.04.5 LTS
- Oracle VirtualBox
- Linux Command Line
- UFW Firewall
- SSH
- Regular Expressions (Regex)
- SHA-256 Hashing
- Windows PowerShell

## Investigation Results

| Security Event | Result |
|---|---|
| Failed local logins | 1 |
| Successful local logins | 2 |
| Brute-force activity | Not identified |
| Unauthorized access | Not identified |
| Incident severity | Informational |
| Classification | Benign User Activity |
| Incident status | Closed |

## Skills Demonstrated
- Linux security hardening
- Authentication log analysis
- Firewall configuration
- Network port enumeration
- SSH service inspection
- Security event correlation
- Incident triage and reporting
- Digital forensic evidence preservation

## Project Evidence
- `auth_evidence_public.log` — Sanitized authentication logs.
- `auth_hash_public.txt` — SHA-256 integrity hash for public evidence.
- `incident_report_public.txt` — Security investigation report.

## Conclusion
The reviewed authentication events were consistent with authorized local user activity. No evidence of brute-force activity or unauthorized access was identified within the reviewed logs.

## Disclaimer
This investigation was conducted in a controlled virtual laboratory. Published evidence has been sanitized to protect personal information. Original forensic evidence is retained privately.
