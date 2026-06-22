# Help Desk Ticket Simulations

## Ticket 001 – Password Reset

### Issue

User was unable to access their account after forgetting their password.

### Resolution

* Opened Active Directory Users and Computers.
* Located the user account.
* Reset the password and required a password change at next logon.
* Verified successful access.

### Technologies Used

* Active Directory Users and Computers
* User Account Management

---

## Ticket 002 – Account Unlock

### Issue

User account became locked after multiple failed login attempts.

### Resolution

* Opened user properties in Active Directory.
* Unlocked the account.
* Verified successful authentication.

### Technologies Used

* Active Directory
* Account Troubleshooting

---

## Ticket 003 – New User Onboarding

### Issue

Provision a new employee account and grant department access.

### Resolution

* Created a new user account.
* Assigned a temporary password.
* Added the user to the appropriate department security group.
* Enabled password change at next logon.

### Technologies Used

* Active Directory
* Security Groups
* Role-Based Access Control

---

## Ticket 004 – Group Membership Modification

### Issue

User required access to department resources.

### Resolution

* Added user to department security group.
* Confirmed membership changes.

### Technologies Used

* Active Directory
* Group Management

---

## Ticket 005 – Employee Offboarding

### Issue

Former employee account required deactivation.

### Resolution

* Disabled the user account.
* Moved the account into a Disabled Users organizational unit.

### Technologies Used

* Active Directory
* User Lifecycle Management

---

## Ticket 006 – Windows 11 Client Deployment

### Issue

Deploy and domain join a Windows 11 workstation.

### Resolution

* Configured networking and DNS settings.
* Joined the workstation to the mullentech.local domain.
* Verified domain authentication.

### Technologies Used

* Windows 11 Pro
* Active Directory
* DNS

---

## Ticket 007 – Group Policy Verification

### Issue

Verify policy deployment to client workstations.

### Resolution

* Executed gpupdate /force.
* Verified applied policies using gpresult /r.

### Technologies Used

* Group Policy Management
* Command Prompt

---

## Ticket 008 – Department Shared Folder Access

### Issue

Provide department users with access to network resources.

### Resolution

* Created a shared folder.
* Configured share and NTFS permissions.
* Verified user access through the network share.

### Technologies Used

* File Shares
* NTFS Permissions
* Access Control

---

## Ticket 009 – Drive Mapping with Group Policy

### Issue

Automatically provide department resources to users.

### Resolution

* Created a Group Policy Object for mapped drives.
* Configured drive mappings for department users.
* Verified access to network resources.

### Technologies Used

* Group Policy Preferences
* File Services

---

## Ticket 010 – DHCP Configuration

### Issue

Automate IP address assignment for domain clients.

### Resolution

* Installed the DHCP Server role.
* Created and activated an IPv4 scope.
* Verified clients received addresses from SERVER01.

### Technologies Used

* DHCP
* Windows Server 2022

---

## Skills Demonstrated

* Active Directory Administration
* Group Policy Management
* User and Group Management
* DNS and DHCP Configuration
* Domain Join Operations
* File Share Management
* NTFS Permissions
* Help Desk Troubleshooting
* Windows Server 2022 Administration
* Windows 11 Administration
