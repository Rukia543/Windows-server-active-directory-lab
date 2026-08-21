# Windows Server 2019 Active Directory Lab

## Overview

Hands-on **Windows Server 2019 systems administration lab** built in VMware Fusion. Configured a small Windows domain environment and practiced core infrastructure, networking, and access-management tasks.

## Environment

| Component             | Configuration                |
| --------------------- | ---------------------------- |
| **Domain Controller** | Windows Server 2019 — `DC01` |
| **Domain**            | `corp.lab`                   |
| **Server IP**         | `10.0.0.160`                 |
| **Client**            | Windows 11 Home              |
| **Client IP**         | `10.0.0.205`                 |
| **Virtualization**    | VMware Fusion                |

## Technologies

**Windows Server 2019 · Active Directory · DNS · DHCP · Group Policy · NTFS · File Sharing · VMware**

## What I Built

* Configured **Active Directory Domain Services** with users, security groups, and Organizational Units
* Configured **DNS and DHCP** for the lab network
* Created and applied a **Workstation Security Policy** using Group Policy
* Configured Windows client networking and verified `corp.lab` connectivity
* Created a departmental network share with **HR, Finance, IT, and Sales** folders
* Configured **share and NTFS permissions** using Active Directory security groups
* Troubleshot DNS, networking, and client/server connectivity

### Connectivity Test

```text
ping corp.lab

Reply from 10.0.0.160
```

### Network Share

\\10.0.0.160\CompanyShares

> **Note:** The Windows 11 Home client was not domain-joined because Windows 11 Home does not support Active Directory domain joining. Network connectivity, DNS resolution, and file-share access were successfully verified.

## Skills Demonstrated

* Windows Server Administration
* Active Directory
* DNS & DHCP
* Group Policy
* User & Group Management
* Network Troubleshooting
* File Sharing
* NTFS Permissions
* VMware Virtualization

## Screenshots

Configuration and testing screenshots are available in the [`screenshots`](./screenshots) folder.

## Key Takeaway

Built and troubleshot a functional Windows Server environment while gaining hands-on experience with **Active Directory, network services, Group Policy, file sharing, and access control**.
