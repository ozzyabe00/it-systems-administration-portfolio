# Help Desk Ticket Troubleshooting Playbook

## Purpose
A collection of real-world support scenarios documented in a consistent format: issue → diagnosis → fix → prevention.

## Ticket Format
**Issue:**  
**Environment:**  
**Impact:**  
**Diagnosis:**  
**Resolution:**  
**Prevention / Notes:**

---

## Ticket 1: User Unable to Log In (AD Lockout)
**Issue:** User cannot log in after multiple attempts  
**Environment:** Windows domain-joined workstation  
**Impact:** User blocked from work  
**Diagnosis:** Account locked out in Active Directory; reviewed failed logons  
**Resolution:** Unlocked account, reset password, confirmed login  
**Prevention / Notes:** Reviewed password policy and advised user on MFA/password manager use

## Ticket 2: Network Drive Missing Intermittently
**Issue:** Shared drive appears sometimes, missing other times  
**Environment:** Windows, domain login, mapped drives via GPO  
**Impact:** User cannot access shared resources  
**Diagnosis:** Checked GPO drive mapping, confirmed AD group membership, verified DNS + connectivity  
**Resolution:** Corrected group membership / mapping scope; forced GP update; validated persistence after reboot  
**Prevention / Notes:** Standardized drive mapping via security groups and documented dependency on VPN
