# Setting up Home Lab to Run Active Directory
![Image of Home Lab we are creating](https://i.imgur.com/6B4ogTE.jpeg)
## Introduction
Welcome! This comprehensive guide is designed to walk you through the process of creating a virtual lab environment using Windows Server, Active Directory Domain Services (AD DS), and a Windows 10 client. Whether you're an IT professional honing your skills or a student learning about network management, this project provides you with a detailed roadmap to configure a fully functional networked environment.

Our journey begins with the critical task of configuring network settings, where you will learn how to differentiate between internal and external connections and assign appropriate IP addresses. We then move on to the essential step of renaming the PC and configuring the internal network adapter, setting the stage for the installation of AD DS. By establishing a new domain, such as mydomain.com, you will gain hands-on experience in creating and managing a centralized directory service.

Further, you'll set up a DHCP server to automatically assign IP addresses to client machines and configure the Routing and Remote Access Service (RRAS) for Network Address Translation (NAT), allowing internal clients to access the internet seamlessly.

To streamline the user creation process, I've included a PowerShell script that automates the generation of multiple user accounts.
## Download Virtualbox
- [Download Virtualbox](https://www.virtualbox.org/wiki/Downloads)
  -   Make sure you also down load the Guest Expansion Pack
## Download Windows 10 and Windows Server
- [Download Windows 10 ISO](https://www.microsoft.com/en-us/software-download/windows10)
- [Download Windows Server 2019 ISO](https://www.microsoft.com/en-us/software-download/windows10)
## Creating our Virtual Machines
### Creating Domain Controller VM
- [Scribe steps to create DC VM](https://scribehow.com/shared/Set_Up_Oracle_VM_VirtualBox_with_Windows_64-bit__onlI_SVqS3S19gA0_8Co7w)
## Set Up IP Addressing
- [Scribe Steps to Set up IP addressing in the Domain Controler](https://scribehow.com/shared/Click_Multiple_Items_in_a_Sequence_Copy__XjaFCM6-QlySrtOtIYzq-Q)
This step identifies which network adapter is internal and which one is to the Internet on the Domain Controller. Further, this sets up DHCP on the Domain Controller. 
## Rename the PC
- [Scribe Steps to Rename the Server PC](
## Install Active Directory Domain Services 
## Create a Dedicated Domain Admin Account
## Create an Organizational Unit
## Create New User
## Make a Domain Admin
## Routing and Remote Access
## Install Nat
## Set up a DHCP Server on the Domain Controller
## DHCP
## Lease Duration
## Configure DHCP Options
## Add an IP Address for a Router
## PowerShell Script
## Create a New VM
## User Config
## Add the Domain Controller
## Address Leases
## Active Directory Users and Computers
