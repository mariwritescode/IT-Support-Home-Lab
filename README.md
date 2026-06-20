# IT-Support-Home-Lab

Windows Server 2025 Active Directory and Help Desk home lab featuring user account management, file share permissions, network drive mapping, DNS troubleshooting, Jira Service Management ticketing, and knowledge base documentation.

## Overview

This project simulates common Help Desk and IT Support tasks in a Windows Server 2025 Active Directory environment.

The lab demonstrates:

- Active Directory administration
- User and group management
- NTFS permissions
- File share permissions
- Network drive mapping
- DNS troubleshooting
- Jira Service Management ticketing
- Technical documentation
- Knowledge Base creation

## Repository Structure

```text
IT-Support-Home-Lab
│
├── Architecture
│
├── Help-Desk-Tickets
│   ├── HD-001-Accounting-Share-Access
│   ├── HD-002-Network-Drive-Missing
│   └── HD-003-DNS-Troubleshooting
│
├── Jira-Service-Management
│
├── Knowledge-Base
│
└── README.md
```

## Environment

### Domain Controller

- Windows Server 2025
- Active Directory Domain Services (AD DS)
- DNS
- File Shares

### Workstation

- Windows 11
- Domain Joined
- User Testing

### Ticketing Platform

- Jira Service Management

## Help Desk Scenarios

### HD-001: User Unable to Access Accounting Share

Troubleshot NTFS permissions preventing access to a departmental file share.

### HD-002: Accounting Network Drive Missing

Restored a missing mapped network drive and verified user access.

### HD-003: Workstation Unable to Resolve Domain Resources

Diagnosed and corrected DNS configuration issues preventing domain resource resolution.
