# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
Northstar Medical Group is a rapidly growing healthcare organization struggling with a disorganized employee onboarding process, resulting in manually created accounts, poorly structured departments, inconsistent access permissions, and overprivileged users. These issues create serious security risks and potential HIPAA and PHI compliance violations due to the lack of a centralized identity management system.

The goal of this project is to build a structured Employee Identity Lifecycle Management Pipeline using Active Directory (NMG.com), implementing departmental organization, employee onboarding, RBAC/ABAC access controls, Group Policy, and standardized account management procedures.

## Solution Overview

The solution was to build a basic employee onboarding pipeline using Active Directory to centralize and standardize identity management. I created an RBAC matrix to ensure employees received access based strictly on their roles and responsibilities, following the principle of least privilege. I also simulated a help desk ticket involving an employee who was provisioned with incorrect access and demonstrated how to identify and resolve the issue.

## Video Walkthrough
[Add your video walkthrough link placeholder here. You will record this tomorrow and update this link so visitors can see a live demonstration of your lab environment.]

## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* UTM
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* Added 4 OUs, Security Groups in each OU and added Users into each OU
* IT Ticket: Corrected incorrect OU assigned to User
