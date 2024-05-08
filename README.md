# Project-2

# Rekall Corporation Penetration Test Report

## Overview
This repository contains the penetration test report for Rekall Corporation. The purpose of this report is to assess the organization's network and systems security, identify vulnerabilities, and provide actionable remediation recommendations.

## Structure
- **Executive Summary:** High-level overview of the test findings, including the strengths and weaknesses of Rekall Corporation's security posture.
- **Detailed Findings:** Comprehensive analysis of vulnerabilities discovered during the assessment.
- **Recommendations:** Suggested remediation measures to strengthen security and address identified weaknesses.

## Collaboration
This work was completed in collaboration with my colleague, **Horya Sediqi**. We began the assessment together, but the specific findings related to the following vulnerabilities were initially identified by Horya:
- **Vulnerability 2: XSS Stored**
  - Type: Windows OS
  - Description: A critical stored XSS was discovered in the comments page.
  - Remediation: Implementation of XSS protection to disallow script code injection.

- **Vulnerability 3: Local File Inclusion**
  - Type: Web App
  - Description: A critical file inclusion vulnerability allowed for the uploading of .php script files.
  - Remediation: Restriction of upload functionality to specific file types using allow listing.

- **Vulnerability 4: Sensitive Data Exposure**
  - Type: Web App
  - Description: Unrestricted access to the robots.txt file exposed sensitive data.
  - Remediation: Restriction of robot.txt access to authorized users.

## References
We have adhered to OpenAI guidelines and standards while utilizing code and tools for penetration testing.

Please review the report for further details and reach out for any additional information.
