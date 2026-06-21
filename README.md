# Azure Identity & Access Management Security Lab

## Overview

This project demonstrates the implementation of identity and access management controls within Microsoft Azure using Microsoft Entra ID.

The objective of the lab was to gain hands-on experience with user administration, security groups, role-based access control (RBAC), authentication security, and audit logging in a cloud environment.

The project was completed using an Azure Free Trial subscription.

---

## Objectives

* Create and manage cloud identities
* Configure security groups
* Implement role-based access control
* Review authentication security controls
* Investigate audit logging capabilities
* Develop familiarity with Microsoft Entra ID

---

## Technologies Used

* Microsoft Azure
* Microsoft Entra ID
* Azure RBAC
* Azure Audit Logs

---

## Environment Configuration

### Resource Group

Resource Group Name:
CyberLab-RG

Purpose:
To organise and manage project resources within Azure.

---

## User Creation

The following users were created to simulate a small organisational environment:

* Adam Admin
* Adam Analyst
* Adam User

These accounts represent administrative, security and standard user roles.

---

## Security Groups

The following security groups were created:

* Administrators
* Security Team
* Employees

Users were assigned to groups according to their responsibilities.

---

## Role-Based Access Control

Role assignments were configured using available Azure built-in roles.

RBAC was implemented to demonstrate the principle of least privilege and access governance.

| User         | Assigned Role |
| ------------ | ------------- |
| Adam Admin   | Reader        |
| Adam Analyst | Reader        |
| Adam User    | Reader        |

Role availability was limited by the Azure Free Trial subscription.

---

## Authentication Controls

Multi-Factor Authentication (MFA) was reviewed as part of the security assessment.

Individual MFA enforcement was unavailable due to subscription-level policy restrictions within the Azure Free Trial environment.

Security Defaults and tenant-level authentication controls were assessed instead.

---

## Audit Logging

Azure Audit Logs were reviewed to identify administrative actions performed during the lab.

Examples included:

* User creation
* Security group creation
* Group membership modifications
* Role assignments

Audit logging provides visibility into changes made within the Azure environment and supports accountability and security monitoring.

---

## Security Principles Demonstrated

* Identity and Access Management (IAM)
* Least Privilege Access
* Role-Based Access Control (RBAC)
* Access Governance
* Authentication Security
* Audit Logging

---

## Lessons Learned

This project provided practical experience with Microsoft Entra ID and Azure identity management.

Key skills developed:

* Managing cloud identities
* Organising users into security groups
* Applying access controls
* Understanding Azure authentication mechanisms
* Reviewing security-related audit logs

Future enhancements may include:

* Microsoft Sentinel integration
* Log Analytics Workspace deployment
* Conditional Access Policies
* Azure Virtual Machines
* Security Monitoring and Alerting
