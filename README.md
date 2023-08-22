# Active-Directory_WinServer
 configure a Windows Server 2019 environment with Active Directory integration, NAT/RAS, DHCP services, and establish internet connectivity while ensuring network security. 
 **Project Title:** Setting up a Secure Windows Server Environment with Active Directory Integration

**Project Objective:**
The objective of this IT project is to configure a Windows Server 2019 environment with Active Directory integration, NAT/RAS, DHCP services, and establish internet connectivity while ensuring network security. This project will follow the steps outlined in Josh Madakor's guide, "How to Setup a Basic Home Lab Running Active Directory," with specific focus on configuring and securing the network environment.

**Project Scope:**
- Configure a Virtual Machine (VM) for the Domain Controller with two Network Interface Cards (NICs).
- Install Windows Server 2019 on the Domain Controller VM.
- Implement Guest Additions CD image to enhance VM functionality.
- Identify and configure the two NICs on the Domain Controller.
- Assign IP address 172.16.0.1 to the internal NIC and set the DNS server to 127.0.0.1.
- Install Active Directory Domain Services on the Domain Controller.
- Configure Active Directory for the domain "mydomain.com."
- Create a Dedicated Admin account for administrative tasks.
- Create an Organizational Unit (OU) and a user (d-jnbaptiste@mydomain.com) and add them to the Admin group.
- Install and configure RAS/NAT services on the Domain Controller.
- Set up a DHCP server on the Domain Controller.
- Utilize a PowerShell script to create mock users.
- Create a Windows 10 Client VM and connect it to the internal network.
- Assign the Windows 10 Client the IP address 172.16.0.100 from the DHCP range 172.16.0.100-200.
- Demonstrate internet connectivity by pinging www.google.com from the Windows 10 Client.
- Rename the Windows 10 Client and join it to the domain "mydomain.com."
- Monitor and confirm active address leases on the Domain Controller.

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

**Project Team:**
- Project Manager: [Your Name]
- System Administrator: [Admin Name]
- Network Engineer: [Engineer Name]
- PowerShell Specialist: [Specialist Name]

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


