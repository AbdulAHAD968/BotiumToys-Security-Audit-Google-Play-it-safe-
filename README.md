# Botium Toys Security Audit

## Overview
This repository contains the documentation and findings from the security audit conducted for Botium Toys as part of the Google Playit Safe course for the Certified Cyber Security certification. The audit covers the entire security program at Botium Toys, focusing on their assets, internal network, and systems.

## Scope and Goals

### Scope
The scope of this audit includes:
- On-premises equipment for in-office business needs
- Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
- Storefront products available for retail sale on-site and online, stored in the company’s adjoining warehouse
- Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
- Internet access
- Internal network
- Data retention and storage
- Legacy system maintenance: end-of-life systems that require human monitoring

### Goals
- Assess existing assets
- Complete the controls and compliance checklist
- Determine which controls and compliance best practices need to be implemented to improve Botium Toys’ security posture

## Current Assets

### Managed by the IT Department
- On-premises equipment
- Employee equipment
- Storefront products and adjoining warehouse
- Systems, software, and services management
- Internet access
- Internal network
- Data retention and storage
- Legacy system maintenance

## Risk Assessment

### Risk Description
- Inadequate management of assets
- Lack of proper controls and compliance with U.S. and international regulations and standards

### Control Best Practices
The first function of the NIST Cybersecurity Framework (CSF) is Identify. Botium Toys needs to:
- Dedicate resources to identify and appropriately manage assets
- Classify existing assets
- Determine the impact of asset loss on business continuity

### Risk Score
- Risk score: 8/10 (high)
- Potential impact from asset loss: Medium
- Risk of fines from governing bodies due to lack of necessary controls and non-compliance: High

### Additional Comments
- All employees have access to internally stored data, including cardholder data and customers’ PII/SPII
- No encryption for customers’ credit card information in the internal database
- Lack of least privilege access controls and separation of duties
- Data integrity controls are in place, and data availability is ensured
- Firewall blocks traffic based on defined security rules
- Antivirus software is regularly monitored
- No Intrusion Detection System (IDS) installed
- No disaster recovery plans or backups of critical data
- Plan to notify E.U. customers within 72 hours of a security breach
- Nominal password policy, not in line with current complexity requirements
- No centralized password management system
- Legacy systems monitored and maintained, but without a regular schedule
- Physical security measures in place (locks, CCTV, fire detection/prevention systems)

## Repository Structure


### Directories and Files
- **audit-reports/**: Contains detailed audit reports and documentation
- **scripts/**: Contains scripts used during the audit for scanning and compliance checking
- **.gitignore**: Specifies files and directories to be ignored by git
- **LICENSE**: License for the repository
- **README.md**: This file

## How to Use

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/botium-toys-security-audit.git

cd botium-toys-security-audit
./scripts/scan-network.sh
python3 scripts/check-compliance.py


This `README.md` provides a comprehensive overview of the project, including the scope and goals of the audit, current assets, risk assessment, repository structure, usage instructions, contribution guidelines, and contact information.
