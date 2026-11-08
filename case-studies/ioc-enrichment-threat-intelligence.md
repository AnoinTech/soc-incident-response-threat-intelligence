# Case Study 2 — IOC Enrichment & Threat Intelligence

**Source:** SEC-320 Lab 2, Group 9 (academic group submission)  
**Type:** Classroom IOC enrichment, ATT&CK mapping, and simulated incident-response exercise

## Objective
Interpret sample indicators of compromise (an IP address, file hash, and domain), organize enrichment findings, relate tactics and techniques to MITRE ATT&CK, and propose a response to a simulated alert.

## Workflow documented in the report
1. Record sample indicators and summarize reported threat-intelligence context.
2. Discuss enrichment sources including **VirusTotal** and **AlienVault OTX**.
3. Map selected techniques to MITRE ATT&CK:
   - **T1566.001** — Spearphishing Attachment
   - **T1003** — OS Credential Dumping
   - **T1071.001** — Application Layer Protocol: Web Protocols
4. Outline a simulated alert response: investigate, classify, propose blocking/isolation, notify the SOC, and consider credential resets.

## Important quality-control observation
The recovered group report attributes the same example MD5 hash to **Emotet** in one section and **Mimikatz** in another. These descriptions conflict. No original screenshots of threat-intelligence lookups or underlying telemetry were retained with this portfolio summary. For this reason, **no malware attribution, vendor score, actor attribution, or live IOC verdict is asserted as verified**.

## What this demonstrates
Familiarity with IOC categories, enrichment workflows, ATT&CK mapping, threat-intelligence reporting, and the importance of validating conflicting security evidence.

## Limitations
This is a historical academic group exercise, not a live investigation or current threat-intelligence feed. Response steps were part of a **simulated scenario** and should not be interpreted as changes made to production systems.

## Attribution
Academic group work by Anointing Ibeh, Elvis Ugbodu, James Hampton, and Mikal Dixon. Individual task ownership was not established in the recovered report.
