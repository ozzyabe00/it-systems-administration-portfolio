# Active Directory Enterprise Lab (Windows Server)

## Objective
Deploy a Windows Server Active Directory environment that simulates a small business domain, including user/group management, basic Group Policy, and secure file sharing.

## Environment
- Windows Server (Domain Controller)
- Windows 10/11 Client VM(s)
- Virtualization: Parallels / VirtualBox / VMware
- Tools: ADUC, Group Policy Management, Event Viewer

## Build Summary
- Installed and promoted a domain controller
- Created OU structure for departments (HR, IT, Sales)
- Created users, groups, and assigned permissions
- Implemented baseline Group Policy:
  - Password policy + account lockout
  - Desktop / control panel restrictions (basic)
- Created file shares and NTFS permissions by group

## Validation & Tests
- Joined a client machine to the domain
- Verified GPO application (`gpresult /r`)
- Tested file share access by department group
- Tested account lockout behavior and reset workflow

## Troubleshooting Scenarios (Documented)
- User can’t log in (locked out / expired password)
- GPO not applying (force update, scope, OU placement)
- Access denied on file share (NTFS vs share perms)

## Evidence
<img width="817" height="737" alt="image" src="https://github.com/user-attachments/assets/b2208d96-2444-481b-a3ba-d7be323cc21e" />

- Domain users & OU structure
- Group Policy settings
- File share permissions
- Client joined to domain + gpresult output

## Outcome (What this proves)
Demonstrates foundational SysAdmin ability with identity management, policy enforcement, and access control in a Windows domain environment.
