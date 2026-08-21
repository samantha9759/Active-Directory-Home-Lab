# Active Directory Home Lab

## Objective
The goal of this lab was to build and configure a basic Active Directory environment using Windows Server. I configured a domain controller, DNS, created domain users, connected a Windows client to the domain, and configured Group Policy. The lab also helped me practice troubleshooting network and domain connectivity issues.

### Skills Learned

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

### Tools Used
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

## Troubleshooting

During the lab, I encountered an issue where the Windows client was unable to locate or connect to the Active Directory domain. I investigated the network configuration and DNS settings on the client and domain controller.

I used Windows command-line tools to diagnose the issue, including:

- `ipconfig /all` — verified IP address, subnet mask, default gateway, and DNS configuration.
- `ipconfig /flushdns` — cleared the local DNS resolver cache.
- `ipconfig /renew` — refreshed the client's IP configuration.
- `ping` — tested connectivity between the client and domain controller.
- `nslookup` — tested DNS name resolution.

After correcting the network/DNS configuration and clearing the DNS cache, I was able to successfully connect the Windows client to the Active Directory domain.

## What I Learned
This lab gave me hands-on experience configuring Active Directory and Windows Server in a virtual environment. I learned how important DNS configuration is for Active Directory domain connectivity and gained practical experience troubleshooting network and domain-related issues.


