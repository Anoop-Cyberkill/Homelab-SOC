# SOC Home Lab

## Project Overview

This project demonstrates a personal Security Operations Center (SOC) home lab created for hands-on cybersecurity and SIEM learning.

The lab is used to practice log collection, SIEM monitoring, authentication-event analysis, security investigation and basic incident detection.

## Lab Architecture

The environment consists of:

* Windows host machine
* Splunk Enterprise
* Windows Security Event Logs
* Sysmon
* Kali Linux virtual machine
* Linux syslog forwarding to Splunk

## Key Activities

* Configured Splunk for security log monitoring
* Collected Windows Security Events
* Configured Sysmon for endpoint visibility
* Investigated failed authentication events
* Practiced SPL searches
* Analyzed security events and timestamps
* Created basic detection searches
* Practiced SOC investigation workflows

## Current Investigation

### Windows Failed Login Analysis

Windows Event ID 4625 is used to identify failed authentication attempts.

The investigation includes:

1. Identifying Event ID 4625 in Splunk
2. Reviewing the target account
3. Checking the logon type
4. Reviewing the failure reason
5. Identifying the source IP when available
6. Correlating failed and successful logons
7. Reviewing related activity
8. Determining whether the activity is expected or requires further investigation

## Repository Contents

### Project Architecture

Contains the architecture/design of the SOC home lab.

### Splunk Screenshots

Contains screenshots demonstrating Splunk configuration, searches and security-event analysis.

### Home Lab Setup

Contains the step-by-step documentation used to build the lab.

## Tools Used

* Splunk Enterprise
* Sysmon
* Windows
* Kali Linux
* SPL
* Windows Security Event Logs
* Linux Syslog

## Learning Objectives

This project is intended to develop practical skills in:

* SIEM monitoring
* Log analysis
* Windows security monitoring
* Linux log analysis
* Authentication-event investigation
* Basic threat detection
* SOC investigation methodology
