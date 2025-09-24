

## Identity & Governance

### Study
- Entra ID (Azure AD): Conditional Access, RBAC, Privileged Identity Management (PIM)  
- Governance: Management Groups, Azure Policy, Blueprints  

### Definitions
# Identity & Governance — Study Notes

## Conditional Access (CA)
**Definition:** Rules that decide if/when a user can access apps (e.g., require MFA, block risky logins).  
**Analogy:** Like a bouncer at a club → checks your ID, decides if you get in, and under what conditions (VIP, no sneakers, etc.).  

## Role-Based Access Control (RBAC)
**Definition:** Assigns permissions based on roles, not individuals.  
**Analogy:** Like a workplace badge → a janitor’s badge opens supply closets, a manager’s badge opens offices, but neither gets access to the CEO’s vault.  

## Privileged Identity Management (PIM)
**Definition:** Just-in-time, time-limited access for admin roles.  
**Analogy:** Like borrowing the keys to a Ferrari → you only get them when needed, for a limited time, and they’re taken back afterward to prevent joyrides.  

## Management Groups
**Definition:** Containers to organize multiple Azure subscriptions under one hierarchy for policy/role inheritance.  
**Analogy:** Like folders on your computer → a parent folder’s rules cascade to all subfolders.  

## Azure Policy
**Definition:** Rules that enforce or audit configurations on resources (e.g., require tags, deny public IPs).  
**Analogy:** Like building codes → you can design any house, but policies enforce fire exits, smoke detectors, and safe wiring.  

## Blueprints
**Definition:** Packages of policies, RBAC, and resource templates you can deploy as a standardized environment.  
**Analogy:** Like a home builder’s floor plan → instead of designing from scratch, you apply a pre-approved design that meets all regulations.  


### Project
- Build a multi-tenant Azure AD lab  
- Add CA policies (MFA for admins, block risky sign-ins)  
- Create test users/groups  
- Design a Management Group hierarchy  
- Add custom Azure Policies (enforce tagging, deny unencrypted storage)  


