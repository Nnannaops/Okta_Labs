# Lab 2: Create Users in Okta

**Objective:** Create and activate a user in Okta.  
**Scenario:** Nina Shah needs access to Okta.

---

## Steps

### Create a User
1. Go to **Admin Console → Directory → People**.
2. Add new person:
   - First name: `Nina`
   - Last name: `Shah`
   - Username: `nina.shah@oktaice.com`
   - Primary email: *your email*
3. Ensure account activates now (don’t set a password).
4. Save and refresh.
5. Confirm Nina’s status = **Pending user action**.

### Modify User Profile
- Add attributes: Title, Phone, User Type, Cost Center, Organization, Department, Region.  
- Save changes.

### Activate Account
- Open activation email.  
- Set password and enroll in Okta Verify MFA.  
- Confirm access to End-User Dashboard.

### Verify in Admin
- Nina’s status = **Active**.  
- Reports → `user.lifecycle` → confirm "create" and "activate" events.

---

## Why This Matters
- **IAM Relevance:** Shows onboarding flow → how new identities are created and verified.  
- **Okta Platform Use:** Demonstrates integration of user attributes, MFA enrollment, and lifecycle logging.  
- **Business Value:** Ensures secure, consistent account creation that’s auditable.
