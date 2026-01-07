# IT Support Ticket Troubleshooting Playbook

## Purpose
This project documents real-world IT support scenarios using a structured troubleshooting approach. Each ticket demonstrates problem diagnosis, resolution, and prevention in a way that mirrors enterprise help desk operations.

## Ticket Format
**Issue:**  
**Environment:**  
**Impact:**  
**Diagnosis:**  
**Resolution:**  
**Prevention / Notes:**  

---

## Ticket 1: User Unable to Log In (Account Lockout)

**Issue:** User unable to log in to workstation  
**Environment:** Windows 10, Active Directory domain  
**Impact:** User unable to perform job duties  
**Diagnosis:** Account locked due to multiple failed login attempts  
**Resolution:** Unlocked account and reset password in Active Directory  
**Prevention / Notes:** Reviewed password policy and advised user on proper login procedures

---

## Ticket 2: Network Drive Missing After Login

**Issue:** Shared network drive intermittently missing  
**Environment:** Windows domain-joined workstation  
**Impact:** User unable to access shared files  
**Diagnosis:** Verified AD group membership and Group Policy drive mapping  
**Resolution:** Corrected group assignment and forced Group Policy update  
**Prevention / Notes:** Standardized access via security groups and documented dependency on VPN

---

## Ticket 3: VPN Connection Fails

**Issue:** User unable to connect to corporate VPN  
**Environment:** Windows laptop, remote connection  
**Impact:** No access to internal resources  
**Diagnosis:** VPN client misconfiguration and outdated credentials  
**Resolution:** Reconfigured VPN client and reauthenticated user  
**Prevention / Notes:** Verified VPN client version and documented configuration steps

---

## Ticket 4: Printer Not Mapping Automatically

**Issue:** Network printer not appearing for user  
**Environment:** Windows domain environment  
**Impact:** User unable to print documents  
**Diagnosis:** Printer deployment not applied due to incorrect group scope  
**Resolution:** Corrected deployment scope and refreshed Group Policy  
**Prevention / Notes:** Validated printer group assignments and documented deployment process

---

## Ticket 5: Outlook Fails to Load Profile

**Issue:** Outlook fails to open user profile  
**Environment:** Windows 10, Microsoft Outlook  
**Impact:** User unable to access email  
**Diagnosis:** Corrupt Outlook profile  
**Resolution:** Recreated Outlook profile and verified mailbox connectivity  
**Prevention / Notes:** Documented profile recreation steps for faster future resolution

---

## Outcome (What this proves)
Demonstrates structured troubleshooting, documentation skills, and real-world IT support experience aligned with enterprise help desk and junior systems administration roles.
