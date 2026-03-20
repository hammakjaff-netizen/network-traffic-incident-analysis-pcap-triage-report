# Network Traffic Incident Analysis and PCAP Triage Report

This repository contains a professional technical assessment report based on packet capture analysis performed in Wireshark for an incident triage scenario.

## Project Summary
The assessment reviewed a captured PCAP file to identify relevant network activity, host communication patterns, protocol behavior, and traffic that may support incident investigation.

The analysis included:
- capture file and metadata review
- HTTP request activity
- TLS handshake analysis
- SMTP communication attempts
- IPv4 and IPv6 endpoint summaries
- SMB / AndX-related traffic
- ARP response review
- prioritization of suspicious traffic for follow-up investigation

## Key Findings
- The capture contained 83,782 packets over approximately 15 minutes.
- The most active systems in the PCAP were `192.168.30.128` and `192.168.30.130`.
- Traffic included HTTP, TLS, SMTP, SMB-related, ARP, IPv4, and IPv6 multicast activity.
- The evidence supported further investigation, but the report avoided overstating suspicious activity as confirmed malicious behavior without corroboration.

## Files
https://github.com/hammakjaff-netizen/network-traffic-incident-analysis-pcap-triage-report/blob/220d3facef6d4f8901aa290eec3ba3ed85ee3732/network_traffic_incident_analysis_pcap_triage_report.pdf

## Notes
This assessment was conducted in a controlled environment for authorized technical analysis and documentation purposes.


