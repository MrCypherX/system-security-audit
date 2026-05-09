# system-security-audit
System Security Audit Internship Task
# System Security Audit (Local Machine)

## Overview

This project is a basic system security audit performed on a Windows-based local machine as part of my Cybersecurity Internship at WeIntern.

## Objectives

* Identify basic vulnerabilities
* Check firewall and antivirus status
* Scan open ports using Nmap
* Review installed software
* Verify Windows update status
* Recommend security improvements

## Tools Used

* Nmap
* Windows Defender
* PowerShell
* Command Prompt
* Windows Security Tools

## Commands Used

```bash
systeminfo
netsh advfirewall show allprofiles
Get-MpComputerStatus
nmap -sV localhost
```

## Findings

* Firewall protection enabled
* Windows updated
* Open ports identified
* Real-Time Protection disabled
* No risky software found

## Recommendations

* Enable Real-Time Protection
* Monitor open ports
* Keep system updated
* Perform regular security scans

## Author

Prathmesh Laxman Talekar
