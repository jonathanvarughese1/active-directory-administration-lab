## active-directory-lab

## Overview

This project demonstrates hands-on experience configuring and administering a Windows Active Directory environment using Windows Server 2022 and Windows 11 Pro in VirtualBox. The lab focuses on domain services, DNS, user and group management, organizational units, and Group Policy administration.

## Lab Environment

## Component

## Configuration

Virtualization

Oracle VirtualBox

Domain Controller

Windows Server 2022 — DC01

Domain

corp.local

Domain Controller IP

192.168.56.10

Client

Windows 11 Pro — WIN11CLIENT

Client IP

192.168.56.20

Network

VirtualBox host-only network

## Implemented Configurations

Configured a Windows Server 2022 domain controller for the corp.local domain.

Configured DNS and client network settings for Active Directory connectivity.

Created and organized test users, groups, and organizational units for Finance, HR, and IT.

Joined a Windows 11 Pro client to the domain and organized its computer account within Active Directory.

Configured baseline Group Policy settings.

Created a Group Policy configuration to manage local administrator membership on the Windows client.

Verified relevant configurations through administrative tools and client-side testing.

## Documentation

screenshots/ — Evidence of domain configuration, directory structure, and policy settings.

documentation/ — Lab architecture, configuration notes, and troubleshooting findings.

powershell/ — Tested PowerShell commands and scripts, where applicable.

## Skills Demonstrated

Active Directory Domain Services (AD DS), DNS, Windows Server administration, user and group management, Group Policy, domain joining, Windows troubleshooting, VirtualBox, and basic network configuration.

## Future Improvements

Potential extensions include additional account security policies, delegated administration, automated account provisioning with PowerShell, and integration with security monitoring tools.
