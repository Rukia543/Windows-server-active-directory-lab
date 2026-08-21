# Windows Server Lab Notes

## Network Configuration

Domain Controller:

- Hostname: DC01
- IPv4: 10.0.0.160
- Subnet Mask: 255.255.255.0
- Domain: corp.lab

Windows Client:

- IPv4: 10.0.0.205
- Subnet Mask: 255.255.255.0
- DNS: 10.0.0.160

## Connectivity Testing

Tested connectivity from the Windows client using:

ping corp.lab

The client successfully resolved corp.lab to 10.0.0.160 and received replies.

## File Share

Created:

C:\CompanyShares

Department folders:

- HR
- Finance
- IT
- Sales

Configured network sharing and NTFS permissions using Active Directory security groups.

## Troubleshooting

During the lab, I encountered networking and DNS issues involving the Windows client and virtual network adapter.

I verified:

- IPv4 configuration
- Subnet configuration
- Default gateway
- DNS configuration
- VM network adapter
- DNS resolution
- ICMP connectivity
- Network share access