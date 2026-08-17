**ISO 27001 Gap Assessment**

**Project Overview**

This project demonstrates a sample ISO 27001 gap assessment of a cybersecurity lab environment.

The purpose of the project is to check whether selected security controls are implemented, identify gaps, assess the risks, and recommend improvements.

Note: This is a portfolio/lab project and is not a formal ISO 27001 certification audit or assessment of a real organization.

**Lab Environment**

The assessment is based on the following cybersecurity lab environment:

Windows Endpoint
Wazuh Agent
Wazuh Cloud
Azure Log Analytics Workspace
Microsoft Sentinel
Vulnerability detection/scanning tools
Test user accounts

**Controls Assessed**

The following six control areas were assessed:

Access Control
Asset Management
Logging & Monitoring
Backup
Vulnerability Management
Incident Management

**Assessment Methodology**

For each control area, the following process was followed:

Identify what the control should achieve.
Check what is currently implemented in the lab.
Record the current practice.
Assign a status such as Compliant, Partial, or Not Demonstrated.
Identify the gap.
Assess the risk associated with the gap.
Recommend a remediation action.
Identify supporting evidence.

**Simple Process**

Control Requirement
        ↓
Current Practice
        ↓
Status
        ↓
Gap
        ↓
Risk
        ↓
Recommendation
        ↓
Evidence

**Key Findings**

Access Control

Access to the lab systems and security platforms is controlled using authentication mechanisms.

Gap: Periodic access review was not demonstrated.

Risk: Medium

Recommendation: Perform periodic access reviews and remove unnecessary access.

**Asset Management**

The main lab assets were identified and documented in an asset inventory.

Status: Compliant

Recommendation: Review and update the inventory periodically.

**Logging & Monitoring**

Windows security logs were collected and analyzed using Wazuh and Microsoft Sentinel/Azure Log Analytics.

Gap: A complete alert → investigation → incident workflow was not demonstrated.

Risk: Medium

Recommendation: Configure and test appropriate detection and alerting rules.

**Backup**

A backup and recovery process was considered for the lab environment.

Gap: Actual backup restoration testing needs to be demonstrated.

Risk: High

Recommendation: Perform a controlled backup and restore test using dummy data and record the recovery results.

**Vulnerability Management**

Vulnerability detection/scanning was practiced using security tools.

Gap: Complete vulnerability remediation tracking from identification to closure was not demonstrated.

Risk: Medium

Recommendation: Track vulnerabilities, severity, affected assets, remediation actions, and closure status.

**Incident Management**

Security monitoring and threat-hunting activities were practiced using Wazuh/Sentinel.

Gap: A complete incident documentation and response workflow was not demonstrated.

Risk: Medium

Recommendation: Create a controlled incident record covering detection, investigation, response, resolution, and closure.

**Project Files**

ISO27001-Gap-Assessment/
│
├── README.md
├── ISO27001_Gap_Assessment.xlsx
├── ISO27001_Gap_Assessment_Report.docx
│
└── Evidence/
    ├── access-control.png
    ├── asset-inventory.png
    ├── wazuh-dashboard.png
    ├── sentinel-logs.png
    ├── vulnerability-scan.png
    ├── backup-test.png
    └── incident-evidence.png
Skills Demonstrated
ISO 27001 concepts
GRC
Gap Assessment
Risk Assessment
Control Assessment
Asset Management
Access Control
Security Logging & Monitoring
Vulnerability Management
Incident Management
Documentation
Remediation Planning

**Disclaimer**

This project is a simulated educational portfolio project based on a cybersecurity lab environment. It does not represent an ISO 27001 certification audit, external audit, or assessment performed for a real organization.
