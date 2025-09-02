# Lab 5: Manage User Account Statuses

**Objective:** Manage account states across lifecycle.  
**Scenarios:** Password reset, expire, lockout, suspension, deactivation.

---

## Steps

### Reset Password
- Admin resets → user sets new password → status: Password reset → Active.

### Expire Password
- Admin issues temp password → user sets new password.

### Lockout
- 10+ failed logins → status: Locked out → admin unlocks.

### Suspend/Deactivate
- Suspend immediately blocks access.  
- Deactivate after 30 days → account closed.

---

## Why This Matters
- **IAM Relevance:** Secure handling of compromised or inactive accounts is a core IAM function.  
- **Okta Platform Use:** Provides automation and logging for compliance/audit.  
- **Business Value:** Protects against breaches, enforces HR/security policies, and prevents orphaned accounts.
