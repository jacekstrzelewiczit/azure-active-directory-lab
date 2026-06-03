# Active Directory Domain Services Lab (Azure)

## Project Overview

This project demonstrates the deployment and configuration of Active Directory Domain Services (AD DS) on a Windows Server 2022 virtual machine hosted in Microsoft Azure.

The lab simulates a basic enterprise identity management environment including domain controller setup, user creation, and authentication validation.

---

## Technologies Used

* Microsoft Azure
* Windows Server 2022
* Active Directory Domain Services (AD DS)
* DNS
* Virtual Machines

---

## Infrastructure Setup

### 1. Active Directory Installation

Installed Active Directory Domain Services (AD DS) on Windows Server 2022 to prepare the environment for centralized identity management.

---

### 2. Domain Controller Promotion

Promoted the Windows Server instance to a Domain Controller and created a new Active Directory forest for centralized authentication and domain management.

---

## User Management

Created a new Active Directory user account and assigned it to the Domain Admins security group.

This demonstrates:

* user creation
* privilege assignment
* basic identity management

---

## Authentication Testing

Validated successful domain authentication using domain administrator credentials within the configured Active Directory environment.

---

## Verification

Confirmed proper Active Directory functionality by:

* logging into the domain environment
* verifying domain identity on the system
* ensuring AD DS and DNS integration working correctly

---

## Skills Demonstrated

* Active Directory administration
* Domain controller setup and configuration
* User and group management
* Identity and access management (IAM)
* Windows Server administration
* DNS and domain integration
* Cloud-based infrastructure (Azure VMs)

---

## Screenshots

### 1. Active Directory Installation
![AD Installation](screenshots/01-ad-role-installation.png)

---

### 2. Domain Controller Promotion
![Domain Controller](screenshots/02-ad-domain-controller.png)

---

### 3. User Creation (Domain Admin)
![User Creation](screenshots/03-ad-create-user.png)

---

### 4. Authentication Test
![Authentication](screenshots/04-ad-authentication.png)

---

### 5. Active Directory Verification
![Verification](screenshots/05-ad-verification.png)
## Summary

This lab demonstrates a complete Active Directory deployment lifecycle in a cloud environment, from installation to validation of a working domain infrastructure.
