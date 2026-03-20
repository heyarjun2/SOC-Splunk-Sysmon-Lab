# SOC Splunk sysmon Lab
Beginner-friendly SOC lab project focused on Windows logging, Splunk detection, and hands-on threat investigation.

## Overview
This project is a hands-on SOC lab built to practice log collection, event monitoring, and basic threat detection using Splunk and Sysmon on a Windows machine.

The goal of this lab is to simulate how a security analyst collects logs, searches for suspicious behavior, and documents findings.

## Tools Used
- Splunk Enterprise / Splunk Free
- Sysmon
- Windows Event Logs
- Splunk Universal Forwarder
- Virtual Machine environment

## Objectives
- Collect Windows and Sysmon logs
- Ingest logs into Splunk
- Detect failed logon attempts
- Detect suspicious PowerShell activity
- Write basic SPL detection queries
- Document findings like a SOC analyst

## Repository Structure
- `docs/` contains setup notes, architecture, and incident reporting
- `detections/` contains SPL queries
- `data/` contains sample exported log data
- `screenshots/` contains evidence from the lab
- `notes/` contains working notes and simulations

## Planned Detection Use Cases
1. Brute-force login attempts
2. PowerShell execution monitoring
3. Suspicious process creation
4. Basic investigation workflow

## Status
Repository structure completed. Lab setup and data collection in progress.
