# Active Directory Home Lab

## Objective
The goal of this lab was to build and configure a basic Active Directory environment using Windows Server. I configured a domain controller, DNS, created domain users, connected a Windows client to the domain, and configured Group Policy. The lab also helped me practice troubleshooting network and domain connectivity issues.
## Languages
  - Powershell
## Lab Environment

- Oracle VirtualBox
- Windows Server
- Windows 10/11 Client
- Active Directory Domain Services
- DNS
- Group Policy
## Skills Learned

- Windows Server administration
- Active Directory Domain Services
- Domain Controller configuration
- DNS configuration and troubleshooting
- IP addressing and TCP/IP networking
- DHCP concepts and network configuration
- Creating and managing Active Directory users
- Joining a Windows client to a domain
- Group Policy Management
- Domain and client troubleshooting
- Basic network connectivity troubleshooting

## Tools Used
- Windows Server
- Windows 10/11 client
- Active Directory Domain Services
- DNS Manager
- Group Policy Management
- Server Manager
- Command Prompt
- Virtual machines
### Troubleshooting Commands
- ipconfig
- ping
- ipconfig /all
- ipconfig /flushdns
- ipconfig /renew
- nslookup
  
## Steps
1. Created the Windows Server virtual machine.
2. Configured the server's network settings and IP address.
3. Installed the Active Directory Domain Services role.
4. Promoted the Windows Server to a Domain Controller.
5. Created the Active Directory domain.
6. Configured and verified DNS.
7. Created user accounts in Active Directory.
8. Configured the Windows client with the correct network and DNS settings.
9. Tested network connectivity between the client and domain controller.
10. Joined the Windows client to the Active Directory domain.
11. Verified the client successfully connected to the domain.
12. Opened Group Policy Management.
13. Created and configured a Group Policy.
14. Applied the policy to the appropriate domain/user/computer.
15. Tested and verified the Group Policy settings.
## ## PowerShell User Creation

To practice Active Directory administration and automation, I used PowerShell to create multiple Active Directory user accounts from a list of names. The script created an `_USERS` Organizational Unit and automatically generated usernames and user accounts.
<img width="638" height="177" alt="Powershell" src="https://github.com/user-attachments/assets/82e12549-67c8-454e-bba9-36ec6e89e06c" />

## Troubleshooting

During the lab, I encountered an issue where the Windows client was unable to locate or connect to the Active Directory domain. I investigated the network configuration and DNS settings on the client and domain controller.

I used Windows command-line tools to diagnose the issue, including:

- `ipconfig /all` — verified IP address, subnet mask, default gateway, and DNS configuration.
- `ipconfig /flushdns` — cleared the local DNS resolver cache.
- `ipconfig /renew` — refreshed the client's IP configuration.
- `ping` — tested connectivity between the client and domain controller.
- `nslookup` — tested DNS name resolution.
## Screenshots

### Server Manager and Role Installation
<img width="502" height="369" alt="server-manager" src="https://github.com/user-attachments/assets/6ae39997-b98b-48a2-b52e-30fe91df59aa" />

### Network Configuration
<img width="478" height="346" alt="network details" src="https://github.com/user-attachments/assets/8d0943e5-04a2-4ec8-a5b1-4b75c0fc8f07" />

### Routing and Remote Access
<img width="320" height="232" alt="configure and enable routing and remote access" src="https://github.com/user-attachments/assets/6cbcb6d6-cab8-4ac8-9f09-349e3c166d19" />
### Group Policy Update
<img width="508" height="352" alt="gp update" src="https://github.com/user-attachments/assets/bcaabbd6-f672-499d-9989-e434c678cb4a" />

After correcting the network/DNS configuration and clearing the DNS cache, I was able to successfully connect the Windows client to the Active Directory domain.

## What I Learned
This lab gave me hands-on experience configuring Active Directory and Windows Server in a virtual environment. I learned how important DNS configuration is for Active Directory domain connectivity and gained practical experience troubleshooting network and domain-related issues.


