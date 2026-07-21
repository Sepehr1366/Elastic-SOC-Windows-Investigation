# Elastic SOC Windows Investigation

## Project Overview

This project demonstrates a hands-on Security Operations Center (SOC)
investigation lab built with the Elastic Stack. Windows endpoint
telemetry is collected with Sysmon and Elastic Agent, then analyzed in
Kibana using KQL to investigate Windows process creation events.

## Lab Architecture

-   Ubuntu VM
    -   Elasticsearch
    -   Kibana
    -   Fleet Server
-   Windows Endpoint
    -   Elastic Agent
    -   Sysmon

## Technologies Used

-   Elastic Security
-   Elasticsearch
-   Kibana
-   Fleet
-   Elastic Agent
-   Sysmon
-   KQL (Kibana Query Language)
-   Windows Event Logs

## Investigation Workflow

1.  Execute a Windows command.
2.  Collect Sysmon Process Creation events.
3.  Search for the event in Kibana.
4.  Review process details and evidence.
5.  Export JSON evidence.
6.  Capture screenshots.
7.  Write a professional SOC investigation report.

## Commands Investigated

-   cmd.exe
-   powershell.exe
-   hostname.exe
-   ipconfig.exe
-   ping.exe
-   net.exe
-   tasklist.exe
-   systeminfo.exe
-   nslookup.exe
-   netstat.exe
-   arp.exe
-   route.exe
-   schtasks.exe
-   sc.exe
-   reg.exe
-   certutil.exe
-   curl.exe

## Skills Demonstrated

-   Windows Endpoint Monitoring
-   Elastic SIEM Investigation
-   KQL Searching
-   Sysmon Event Analysis
-   Process Creation Analysis
-   Threat Hunting Fundamentals
-   Security Event Documentation

## Repository Structure

``` text
reports/
screenshots/
evidence/
images/
README.md
```

## MITRE ATT&CK

Examples of techniques related to the investigated activity include:

-   T1059 -- Command and Scripting Interpreter
-   T1016 -- System Network Configuration Discovery
-   T1082 -- System Information Discovery

## Future Improvements

-   Add detection rules
-   Create Kibana dashboards
-   Add Sigma detection rules
-   Expand investigations with suspicious PowerShell scenarios

## Author

**Sepehr Naji**

CompTIA Security+ \| Computer Science Graduate \| SOC Analyst Candidate
