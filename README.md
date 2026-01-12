# Active-Directory-
Hands on Active Directory labs focused on user and account management
Active Directory Labs
Create a New Domain User


Lab Overview
This lab documents the process of creating a new domain user in Active Directory using Active Directory Users and Computers (ADUC). The objective is to demonstrate a core IT Help Desk task related to user onboarding within a Windows domain environment.
The lab focuses on:


Organizational Unit selection


User identity configuration


Password policy enforcement


Verification of successful account creation



Environment and Technologies Used


Active Directory Domain Services (AD DS)


Active Directory Users and Computers (ADUC)


Windows Server Domain Controller



Operating System


Windows Server



High-Level Deployment and Configuration
A Windows Server was configured as a Domain Controller with Active Directory Domain Services installed. Organizational Units were structured to organize users by role. User account management tasks were performed using the Active Directory Users and Computers console.

Lab Walkthrough
Step 1 – Opening Active Directory Users and Computers

The Active Directory Users and Computers console is opened to manage objects within the mydomain.com domain. Existing Organizational Units such as _ADMINS, _CLIENTS, and _EMPLOYEES are visible.

Step 2 – Selecting the Employees Organizational Unit

The _EMPLOYEES Organizational Unit is selected to ensure the new user account is created in the appropriate container.

Step 3 – Initiating New User Creation

Within the selected Organizational Unit, the context menu is used to navigate to New → User to begin the user creation process.

Step 4 – Entering User Identity Information

The user’s first name, last name, and logon name are entered. Both the User Principal Name (UPN) and the pre–Windows 2000 logon name are automatically generated and reviewed.

Step 5 – Configuring Initial Password Settings

An initial password is assigned to the user account. The option User must change password at next logon is enabled to align with standard security practices.

Step 6 – Confirming User Creation

A summary screen displays the user account details. The Finish option is selected to complete the user creation process.

Step 7 – Verifying User Account and Group Membership

The newly created user account is opened to confirm successful creation and verify default group membership, including membership in the Domain Users group.

Outcome
A new domain user account was successfully created within the designated Organizational Unit. The account was configured with appropriate login credentials and default security settings, validating foundational Active Directory user management functionality.

Notes for You (not part of the README)


This is exactly the right level for an entry-level AD lab


Your next lab should live below this one in the same repo


Do not over-expand this README yet


Next logical additions:


Reset user password and unlock account


Account lockout troubleshooting


When you want to add the next lab, I’ll append it cleanly without breaking this structure.
