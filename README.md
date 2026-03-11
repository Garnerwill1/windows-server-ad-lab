# Windows Server Active Directory Lab

## Overview
In this lab, I built a Windows Server 2022 domain controller in VMware and configured an on-premises Active Directory environment from scratch. I created a custom OU structure, added Marvel and DC-themed users, created security groups, and assigned users to groups to simulate a real administrative environment.

## Lab Objectives
- Install Windows Server 2022 in VMware
- Configure a static IP address
- Rename the server to DC01
- Install Active Directory Domain Services (AD DS)
- Promote the server to a domain controller
- Create a new Active Directory domain
- Build an OU structure for administration and users
- Create Marvel and DC user accounts
- Create security groups
- Assign users to groups based on job function

## Environment
- **Hypervisor:** VMware Workstation
- **Operating System:** Windows Server 2022 Standard Evaluation (Desktop Experience)
- **Server Name:** DC01
- **Domain Name:** garnerlab.local

## Configuration Steps
1. Created a Windows Server 2022 virtual machine in VMware
2. Configured a static IP address for the server
3. Renamed the server to **DC01**
4. Installed **Active Directory Domain Services**
5. Promoted the server to a domain controller
6. Created a new forest and domain: **garnerlab.local**
7. Opened **Active Directory Users and Computers**
8. Created the following Organizational Units:
   - Admins
   - Corp Users
   - Groups
   - Servers
9. Created sub-OUs under **Corp Users**:
   - Marvel
   - DC
10. Created user accounts in each OU
11. Created security groups in the **Groups** OU
12. Added users to the appropriate groups

## OU Structure
- **Admins**
- **Corp Users**
  - **Marvel**
  - **DC**
- **Groups**
- **Servers**

## Users Created

### Marvel
- Peter Parker
- Tony Stark
- Steve Rogers
- Natasha Romanoff
- Bruce Banner

### DC
- Clark Kent
- Bruce Wayne
- Hal Jordan
- Barry Allen
- Arthur Curry

## Security Groups Created
- Helpdesk
- HR
- IT Admins
- Finance
- Security

## Group Membership Assignments

### Helpdesk
- Peter Parker
- Barry Allen

### HR
- Steve Rogers
- Clark Kent

### IT Admins
- Tony Stark
- Bruce Wayne

### Finance
- Bruce Banner
- Arthur Curry

### Security
- Natasha Romanoff
- Hal Jordan

## Skills Demonstrated
- Windows Server administration
- Active Directory Domain Services
- Domain controller deployment
- Organizational Unit design
- User account provisioning
- Security group creation
- Group membership management
- VMware virtualization
- Basic identity and access administration

## Screenshots
Add your screenshots here:
- OU structure
- Marvel users
- DC users
- Groups
- Group memberships

## Key Takeaway
This lab helped me practice core system administration tasks in an on-prem Active Directory environment, including domain setup, directory organization, user provisioning, and group-based administration.
