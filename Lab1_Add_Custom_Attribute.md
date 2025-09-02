# Lab 1: Add a Custom Attribute

**Objective:** Add a custom attribute to track regions for users.  
**Scenario:** The organization wants to capture user regions (AMER, APAC, EMEA).

---

## Steps
1. Go to **Admin Console → Directory → Profile Editor**.
2. Select the **Okta User (default)** profile.
3. Add attribute:
   - Data type: `String`
   - Display name: `Region`
   - Variable name: `region`
   - Description: `Geographic region`
4. Define enumerated values:
   - AMER
   - APAC
   - EMEA
5. Set permissions = **Read Only**.
6. Save changes.

---

## Why This Matters
- **IAM Relevance:** Custom attributes extend the identity schema to store metadata needed for policies, provisioning, and reporting.  
- **Okta Platform Use:** The "Region" attribute can later be used in **Group Rules**, **Conditional Access Policies**, and **Licensing Decisions**.  
- **Business Value:** Provides fine-grained control aligned with global workforce needs.
