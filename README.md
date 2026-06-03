# qradar-authentication-failure-investigation

A beginner-friendly cybersecurity project focused on detecting authentication failures and identifying possible brute-force attacks using QRadar SIEM concepts and Python log analysis.

---

## Project Overview

This project simulates a Security Operations Center (SOC) investigation workflow by:
- Parsing authentication logs
- Detecting failed login attempts
- Identifying brute-force attack behavior
- Creating QRadar-style detection logic
- Documenting incident findings

The goal of this project is to demonstrate:
- SIEM fundamentals
- Detection engineering
- Security log analysis
- Incident investigation
- Basic automation using Python

---

## Features

- Authentication failure detection
- Brute-force attack identification
- QRadar detection rule example
- Root Cause Analysis (RCA) documentation
- Sample security logs
- Python-based log parser

---

## Project Structure

```bash
qradar-authentication-failure-investigation/
│
├── logs/
│   └── sample_logs.txt
│
├── rules/
│   └── qradar_rule.txt
│
├── docs/
│   └── root_cause_analysis.md
│
├── parse_logs.py
├── requirements.txt
├── .gitignore
├── README.md
