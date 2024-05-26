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
- [Scribe Steps to Set up IP addressing in the Domain Controler](https://scribehow.com/shared/IP_Addressing__ae6PO3kATcqn08EPvLDepA)</br>
This step identifies which network adapter is internal and which one is to the Internet on the Domain Controller. Further, this sets up DHCP on the Domain Controller. 
## Rename the PC
- [Scribe Steps to Rename the Server PC](https://scribehow.com/shared/Rename_the_PC__ajy7-MPNT2erFbgOqeNqOg)</br>

## Install Active Directory Domain Services 
- [Scribe Steps to Install AD DS](https://scribehow.com/shared/Install_Active_Directory_Domain_Services__Nd42lC1tTkamlCkZswfHmQ)</br>

## Create a Dedicated Domain Admin Account
- [Scribe Steps to Create Dedicated Domain Admin Account](https://scribehow.com/shared/Created_Dedicated_Domain_Admin_Account__0mcNvFaZRsCrkct__7hZ7A)</br>
## Create a New User
- [Scribe Steps to Create a New User](https://scribehow.com/shared/Create_a_New_User__TG9A72tyTh2wZ7TANmF7uA)</br>
## Routing and Remote Access and installing NAT
- [Scribe Steps Routing and Remote Access and installing NAT](https://scribehow.com/shared/Routing_and_installing_NAT__CDw6SGi1Q--78iUwSUaPFw)</br>
This step shows how to set up routing from the DC to teh CLIENT1 VM. ALso, there seems to be an error when you try to install NAT. So you may have to back out to the Server Manager at somepoint, which is why I added those steps in the link.

## Set up a DHCP Server on the Domain Controller
- [Scribe Steps to Set up a DHCP Server on the Domain Controller](https://scribehow.com/shared/Set_Up_DHCP_on_Domain_Controller__VDLK0ocpTwqVpRSTKMJCGg)</br>
## PowerShell Script
- [Scribe Steps to Install AD DS](https://scribehow.com/shared/Install_Active_Directory_Domain_Services__Nd42lC1tTkamlCkZswfHmQ)</br>
## Create a New VM
- [Scribe Steps to Install AD DS](https://scribehow.com/shared/Install_Active_Directory_Domain_Services__Nd42lC1tTkamlCkZswfHmQ)</br>
## User Config
- [Scribe Steps to Install AD DS](https://scribehow.com/shared/Install_Active_Directory_Domain_Services__Nd42lC1tTkamlCkZswfHmQ)</br>
## Add the Domain Controller
- [Scribe Steps to Install AD DS](https://scribehow.com/shared/Install_Active_Directory_Domain_Services__Nd42lC1tTkamlCkZswfHmQ)</br>
## Address Leases
- [Scribe Steps to Install AD DS](https://scribehow.com/shared/Install_Active_Directory_Domain_Services__Nd42lC1tTkamlCkZswfHmQ)</br>
## Active Directory Users and Computers
- [Scribe Steps to Install AD DS](https://scribehow.com/shared/Install_Active_Directory_Domain_Services__Nd42lC1tTkamlCkZswfHmQ)</br>
