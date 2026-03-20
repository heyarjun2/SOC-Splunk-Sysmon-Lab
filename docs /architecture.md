# Architecture

## Simple Flow
Windows Machine -> Sysmon + Event Logs -> Splunk Universal Forwarder -> Splunk Index -> SPL Searches -> Investigation

## Components
- Windows endpoint generates logs
- Sysmon adds deeper visibility into process activity
- Splunk receives and indexes logs
- Analyst uses SPL queries to investigate suspicious activity
