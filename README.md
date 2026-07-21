# Phishing Investigation Project

## Objective
Investigate a suspected phishing email, extract indicators of compromise (IOCs), analyse headers, inspect URLs, and determine threat level.

## Tools Used
MXToolBox, VirusTotal, Cisco Talos, AbuseIPDB, Splunk, Zeek

## Steps Taken
Collected email headers and extracted sender IP.
Performed DNS, SPF, DKIM, and DMARC checks.
Inspected embedded URLs using MXToolBox and VirusTotal.
Checked IP reputation using Cisco Talos and AbuseIPDB.
Searched Splunk logs for related activity.
Used Zeek to analyse HTTP and DNS traffic.
Mapped findings to MITRE ATT&CK (T1566.002, T1204).

## Findings
Malicious domain with poor reputation.
URL redirected to credential harvesting page.
Sender IP associated with known phishing campaigns.

## MITRE ATT&CK Mapping
T1566.002 — Spearphishing Link
T1204 — User Execution

## What I Learned
Email header analysis, IOC enrichment, URL inspection, threat scoring, and SOC triage workflow.
