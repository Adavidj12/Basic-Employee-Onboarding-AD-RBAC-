# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
Northstar Medical Group is a fictional company. Their active Directory environment has fallen into disarray after years of management by an external MSP with no documented processes or governance:
Ad-hoc user management — accounts are created manually and inconsistently, with no standardized structure.
Broken access control — users frequently have excessive permissions or lack the access they need; department/group organization is chaotic.
No offboarding discipline — departed employees' accounts sometimes remain active for months, creating serious security exposure.
Slow, undocumented onboarding — new hires wait days for access because no process exists or is written down
Northstar Medical Group operate in healthcare, so this isn't just an IT housekeeping issue — it's a HIPAA compliance risk.

## Solution Overview
In this project the solution was for us to bring order to the chaos: documenting our AD structure, establishing proper user lifecycle processes (onboarding/offboarding), enforcing least-privilege access, and building an identity infrastructure that will survive an audit. I built an onboarding pipeline for Northstar employees in Windows server active directory, Cover the new domain creation, the structural OU design, the security groups, the flat RBAC model, and user provisioning was secured.]

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
* Created a Static IP for NMG.com
* Created Organisational Units (OU)
* Added Users to the four OUs created
* Added Users in to their respective security groups.
* Resolved ticket number NMG-0047 through proper investigation of the root cause, developed a hypothesis, Cross checked the hypothesis and finally resolving the issue with detailed documentation. 
