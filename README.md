# Mediroza General Hospital – Penetration Testing

## Overview

This project documents an authorized black-box penetration testing assessment
performed against the Mediroza General Hospital web application.

The assessment followed a structured methodology covering:

- Website Footprinting
- Initial Access
- SQL Injection / Authentication Testing
- Data Extraction
- PDF Password Protection Assessment
- Directory Enumeration
- Sensitive Data Exposure
- Security Reporting

## Assessment Milestones

### M1 – Initial Access
- Web application reconnaissance
- Patient portal authentication testing
- SQL injection testing
- Access-control validation

### M2 – Data Extraction
- Identification of protected pathology reports
- PDF password-protection assessment
- Controlled password-recovery testing
- Validation of recovered documents

### M3 – Critical Data Exposure
- Public directory listing
- Historical database backup exposure
- Staff information exposure
- Shareholder information exposure
- Application file disclosure

### M4 – Reporting
A professional penetration-testing report was prepared containing:

- Executive Summary
- Scope
- Methodology
- Findings
- Evidence
- Impact Assessment
- Remediation Recommendations
- Evidence Register

## Tools Used

- Kali Linux
- cURL
- WHOIS
- Burp Suite
- SQL injection testing techniques
- PDF password-recovery tooling
- Web browser
- Git / GitHub

## Findings

| ID | Finding | Severity |
|---|---|---|
| F-01 | SQL Injection / Authentication Bypass | Critical |
| F-02 | Public Database Backup Exposure | Critical |
| F-03 | Weak PDF Password Protection | High |
| F-04 | Directory Listing | High |
| F-05 | Authentication Information Disclosure | Medium |

## Report

The detailed penetration-testing report is available in:

`report/Mediroza_Penetration_Test_Report_M1_M4_Final.docx`

## Disclaimer

This repository documents an authorized security assessment.
The techniques described must only be performed against systems for which
explicit authorization has been obtained.

Sensitive evidence should not be redistributed or published without
appropriate authorization.