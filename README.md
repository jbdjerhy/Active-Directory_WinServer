# Active-Directory_WinServer
 configure a Windows Server 2019 environment with Active Directory integration, NAT/RAS, DHCP services, and establish internet connectivity while ensuring network security. 
 **Project Title:** Setting up a Secure Windows Server Environment with Active Directory Integration

**Project Objective:**
The objective of this IT project is to configure a Windows Server 2019 environment with Active Directory integration, NAT/RAS, DHCP services, and establish internet connectivity while ensuring network security. This project will follow the steps outlined in Josh Madakor's guide, "How to Setup a Basic Home Lab Running Active Directory," with specific focus on configuring and securing the network environment.

**Project Scope:**
![Picture1](https://github.com/jbdjerhy/Active-Directory_WinServer/assets/142699688/3b98aca0-1ad6-41bc-a83f-53f2e39ddef2)

- Configure a Virtual Machine (VM) for the Domain Controller with two Network Interface Cards (NICs).
- ![Picture2](https://github.com/jbdjerhy/Active-Directory_WinServer/assets/142699688/4bd36b18-b9dd-46bf-b56f-3e11b940e6ec)
- Install Windows Server 2019 on the Domain Controller VM.
- ![Picture3](https://github.com/jbdjerhy/Active-Directory_WinServer/assets/142699688/86e2717c-923c-439a-9770-5fcb4508b1d8)
- Implement Guest Additions CD image to enhance VM functionality.
- Identify and configure the two NICs on the Domain Controller.
- ![Picture4](https://github.com/jbdjerhy/Active-Directory_WinServer/assets/142699688/a0e282e8-70c6-4c84-ae46-bdbfef320114)
- Assign IP address 172.16.0.1 to the internal NIC and set the DNS server to 127.0.0.1.
- ![Picture5](https://github.com/jbdjerhy/Active-Directory_WinServer/assets/142699688/a0e05f26-2122-431e-92ac-6a3bc6355576)
- Install Active Directory Domain Services on the Domain Controller.
- ![Picture6](https://github.com/jbdjerhy/Active-Directory_WinServer/assets/142699688/ed1689be-0676-4bdf-bc54-ba7462bf309e)
- Configure Active Directory for the domain "mydomain.com."
- ![Picture7](https://github.com/jbdjerhy/Active-Directory_WinServer/assets/142699688/402a67d6-fe47-48c7-9fba-9d2f1154ec5d)
- Create a Dedicated Admin account for administrative tasks.
- Create an Organizational Unit (OU) and a user (d-jnbaptiste@mydomain.com) and add them to the Admin group.
- ![Picture8](https://github.com/jbdjerhy/Active-Directory_WinServer/assets/142699688/aab185e2-00da-4147-ab47-5551bb8afc8f)
- Install and configure RAS/NAT services on the Domain Controller.
- ![Picture9](https://github.com/jbdjerhy/Active-Directory_WinServer/assets/142699688/35e4c140-1189-4709-b019-5bd9f0511bb7)
- Set up a DHCP server on the Domain Controller.
- ![Picture10](https://github.com/jbdjerhy/Active-Directory_WinServer/assets/142699688/cee1a4bb-f545-4d36-86a3-e536d96219d6)
- Utilize a PowerShell script to create mock users.
- ![Picture11](https://github.com/jbdjerhy/Active-Directory_WinServer/assets/142699688/c2df7634-a0f7-4075-b28b-206062f25357)
- ![Picture12](https://github.com/jbdjerhy/Active-Directory_WinServer/assets/142699688/87f33a5e-e460-48d0-822a-68ac3b7bf8d0)
- Create a Windows 10 Client VM and connect it to the internal network.
- ![Picture13](https://github.com/jbdjerhy/Active-Directory_WinServer/assets/142699688/3015922e-c2a5-4f87-95e1-61b4b97ea050)
- Assign the Windows 10 Client the IP address 172.16.0.100 from the DHCP range 172.16.0.100-200.
- Demonstrate internet connectivity by pinging www.google.com from the Windows 10 Client.
- ![Picture14](https://github.com/jbdjerhy/Active-Directory_WinServer/assets/142699688/f5a9cf7a-4056-437e-9944-f26dd23c0107)
- Rename the Windows 10 Client and join it to the domain "mydomain.com."
- Monitor and confirm active address leases on the Domain Controller.
- ![Picture15](https://github.com/jbdjerhy/Active-Directory_WinServer/assets/142699688/d4a9405a-8fd3-4c72-b2f0-fd911276f770)

**Project Deliverables:**
- Configured Domain Controller VM with dual NICs.
- Windows Server 2019 installed and properly configured.
- Active Directory Domain Services set up for "mydomain.com."
- Dedicated Admin account and OU/user created.
- RAS/NAT and DHCP services configured.
- PowerShell script for creating mock users.
- Windows 10 Client VM integrated with the network.
- Demonstrated internet connectivity from the Windows 10 Client.
- Successfully joined the Windows 10 Client to "mydomain.com."

**Project Dependencies:**
- Availability of hardware and virtualization software.
- Access to Windows Server 2019 installation media.
- Access to Josh Madakor's guide for reference.

**Project Success Criteria:**
The project will be considered successful when:
- The Windows 10 Client is integrated with the domain.
- Internet connectivity from the Windows 10 Client is confirmed.
- All configuration steps are documented.
- The network is secure and stable.


