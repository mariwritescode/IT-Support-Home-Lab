# HD-003: DNS Troubleshooting

## Incident Summary

A workstation was unable to properly resolve domain resources within the RockyPetSupply.local environment.

## Environment

* Domain: RockyPetSupply.local
* Domain Controller: RPS-DC01
* DNS Server: 192.168.10.10
* Workstation: RPS-WS01

## Problem

The workstation experienced name resolution issues when attempting to access domain resources.

## Investigation

* Verified network connectivity.
* Performed DNS testing using nslookup.
* Reviewed workstation DNS configuration.
* Compared current settings against the domain controller configuration.

## Root Cause

The workstation was configured with an incorrect DNS server, preventing Active Directory name resolution.

## Resolution

* Updated the Preferred DNS Server to 192.168.10.10.
* Flushed the DNS resolver cache.
* Retested domain name resolution.

## Verification

The workstation successfully resolved RockyPetSupply.local using nslookup and domain resources became accessible.

## Skills Demonstrated

* DNS Troubleshooting
* Active Directory Support
* Network Troubleshooting
* Windows Administration
* Incident Documentation

## Supporting Screenshots

DNS configuration
<img width="1022" height="851" alt="Workstation Joined to Domain" src="https://github.com/user-attachments/assets/df0ecf48-9aae-4d44-979e-acf0a1dcf2cc" />
Failed name resolution
<img width="1022" height="848" alt="DNS wrong" src="https://github.com/user-attachments/assets/18b7cd18-2c39-4963-b791-4e664dd474b6" />
DNS correction
<img width="1402" height="1122" alt="Correct DNS (Rocky)" src="https://github.com/user-attachments/assets/6e46bdab-9db8-47bc-9583-e53bae4a93cf" />
Successful nslookup
<img width="1020" height="849" alt="Resolution" src="https://github.com/user-attachments/assets/4bc8d727-ad40-4bc1-9919-d3438f8157dc" />
