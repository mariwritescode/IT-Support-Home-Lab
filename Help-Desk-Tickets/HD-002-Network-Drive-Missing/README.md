# HD-002: Accounting Network Drive Missing

## Incident Summary

User Penny Paws reported that the mapped Accounting (A:) network drive was no longer visible in File Explorer.

## Environment

* Domain: RockyPetSupply.local
* Domain Controller: RPS-DC01
* Workstation: RPS-WS01
* User: Penny Paws
* Network Share: \RPS-DC01\Accounting

## Problem

The Accounting network drive had disappeared from the workstation, preventing access to department files.

## Investigation

* Verified connectivity to the domain controller.
* Confirmed the Accounting share existed on the server.
* Reviewed existing mapped drives.
* Examined network drive configuration.

## Root Cause

The network drive mapping had been removed from the workstation.

## Resolution

* Remapped drive A: to \RPS-DC01\Accounting.
* Enabled reconnect at sign-in.
* Verified successful connection to the shared folder.

## Verification

The Accounting drive appeared in File Explorer and the user successfully opened Quarterly_Budget.txt.

## Skills Demonstrated

* Network Drive Mapping
* File Share Administration
* Windows Troubleshooting
* End-User Support
* Incident Documentation

## Supporting Screenshots

Accounting drive available to the user
<img width="1369" height="1149" alt="Mapped Drive (dog)" src="https://github.com/user-attachments/assets/aa037ca5-f494-40ca-b6f0-684b7655af38" />
Accounting drive missing from File Explorer
<img width="1376" height="1143" alt="Missing Drive (dog)" src="https://github.com/user-attachments/assets/e31cee60-d111-46db-a1d6-175ec0b4fc78" />
Map Network Drive wizard used to restore access
<img width="1377" height="1142" alt="Re-mapping Drive (dog)" src="https://github.com/user-attachments/assets/d7a0785c-40fa-44df-b6c3-0eaa970326a9" />
Accounting drive restored and Quarterly_Budget.txt opened successfully
<img width="1374" height="1145" alt="Resolution (dog)" src="https://github.com/user-attachments/assets/72eb3a4c-e5e5-402d-984a-41bacc3e92cf" />
