# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
Northstar Medical Group relied on a third-party MSP that managed identity and access in an inconsistent, largely manual way as the company grew. The Active Directory environment lacked a clear organizational structure, standardized user provisioning, and role-based access controls, which led to inconsistent permissions and difficult account management. Because access was often assigned manually and without a standardized process, the organization had limited visibility into who had access to sensitive systems and data. This created operational inefficiencies, increased the risk of excessive or inappropriate access, and introduced potential HIPAA compliance concerns.

## Solution Overview
I built a new Active Directory domain for Northstar Medical Group to create a more organized and secure identity and access environment. I designed a clear OU structure for Finance, HR, IT, and Operations so users could be managed consistently by department. I created department-based security groups and implemented a flat RBAC model so access could be assigned based on job role instead of manually on a case-by-case basis. I also provisioned user accounts using consistent naming conventions, department attributes, and group assignments to improve accuracy and reduce access errors. This structure strengthened access control, simplified user management, and created a more secure and auditable onboarding process. I also simulated a mock ticket where a user was provisioned the incorrect level of access! 

## Video Walkthrough
[https://www.loom.com/share/b54ec916c2aa47deb4110b86a31cda37 ]

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
* Solved a mock ticket where a user was given incorrect access!
* I fully documented my steps end-to-end

