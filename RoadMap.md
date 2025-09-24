# AZ-305 Study + Project Roadmap

A 6-week plan that blends **exam preparation** with **hands-on portfolio projects** so you finish with both the **AZ-305 certification** and **tangible architect-level deliverables**.

---

## Week 1–2: Identity & Governance

### Study
- Entra ID (Azure AD): Conditional Access, RBAC, Privileged Identity Management (PIM)  
- Governance: Management Groups, Azure Policy, Blueprints  

### Project
- Build a multi-tenant Azure AD lab  
- Add CA policies (MFA for admins, block risky sign-ins)  
- Create test users/groups  
- Design a Management Group hierarchy  
- Add custom Azure Policies (enforce tagging, deny unencrypted storage)  

### Deliverables
- **GitHub:** Terraform/Bicep templates for MG hierarchy + policies  
- **Diagram:** Management Group + Policy enforcement flow  
- **Blog/LinkedIn:** “How I Built a Secure Azure AD Governance Model with Policies & PIM”  

---

## Week 2–3: Networking & Security

### Study
- Virtual Networks, Subnets, Peering, Private Endpoints  
- Azure Firewall vs NSGs vs Application Gateway vs WAF  

### Project
- Deploy hub-and-spoke VNet with Terraform/Bicep  
- Secure spokes with NSGs, UDRs, and Private Endpoints  
- Add Azure Firewall or App Gateway + WAF in hub  

### Deliverables
- **GitHub:** IaC templates + README  
- **Diagram:** Hub-Spoke with layered security  
- **Blog/LinkedIn:** “Hub-Spoke Network with Terraform: Secure & Scalable”  

---

## Week 3–4: Storage & Data

### Study
- Storage redundancy: LRS, ZRS, GRS  
- SQL Managed Instance vs Cosmos DB vs Azure SQL Database (when to use which)  

### Project
- Deploy multi-tier app: Web App → SQL MI → Blob Storage  
- Secure data layer with private endpoints + managed identity  
- Configure redundancy + performance tiering  

### Deliverables
- **GitHub:** ARM/Bicep templates for app infra + connection strings  
- **Diagram:** App + DB + Storage design  
- **Blog/LinkedIn:** “Designing High-Availability Storage & Data Solutions in Azure”  

---

## Week 4–5: BCDR & Monitoring

### Study
- Azure Site Recovery, Backup Vaults  
- Monitoring with Log Analytics, Azure Monitor, Application Insights  

### Project
- Simulate failover of app to another region with ASR  
- Add Backup Vaults for DB + Storage  
- Build monitoring dashboards in Log Analytics + Application Insights  

### Deliverables
- **GitHub:** Scripts + failover documentation  
- **Screenshots:** Dashboard queries & ASR test failover results  
- **Blog/LinkedIn:** “Designing for Resiliency: BCDR + Monitoring in Azure”  

---

## Week 6: Cost Optimization & Exam Review

### Study
- Cost Management, Reservations, Spot VMs, Hybrid Benefit  
- Review AZ-305 exam blueprint + take practice tests  

### Project
- Run a cost analysis in lab  
  - Compare PAYG vs Reserved Instances  
  - Add autoscaling to app  
  - Document savings + trade-offs  

### Deliverables
- **GitHub:** Autoscale configs + Cost Analysis doc  
- **Diagram:** Cost-optimized deployment  
- **Blog/LinkedIn:** “How to Optimize Azure Costs Without Sacrificing Performance”  

---
## Capstone

### Role Play Scenarios

These scenarios are designed to practice **consultant-style conversations** — exactly what ProServ and Solutions Architects face with customers.  
They help you move beyond “what Azure can do” into **how to explain its value** in business terms.  

### Scenario 1: Azure Site Recovery (ASR)
**Character:** Samantha, IT Director at Contoso Financial Services  
**Context:** She’s considering increasing the budget to roll out Azure Site Recovery (ASR).  
**Her Questions:**  
- What exactly does ASR do?  
- What types of failures does it protect against?  
- Why is it worth investing in if backups already exist?  

**Your Goal:** Explain ASR in plain language:  
- Contrast backups vs. replication/failover.  
- Emphasize RPO/RTO, regional failover, and compliance.  
- Position ASR as protecting revenue and reputation by reducing downtime.  

---

### Scenario 2: Azure Key Vault
**Character:** Jax, Co-Cloud Administrator at Contoso Financial Services  
**Context:** He’s tasked with implementing Azure Key Vault but isn’t clear why it’s needed since Azure already encrypts data at rest and in transit by default.  
**His Questions:**  
- Why use Key Vault when encryption is built-in?  
- What unique purpose does Key Vault serve?  
- How does it help with secrets, keys, and certificate management?  

**Your Goal:** Explain Key Vault in plain language:  
- Highlight central secret management and rotation.  
- Explain separation of duties: apps don’t store creds, they fetch them securely.  
- Tie back to compliance, auditability, and reduced insider risk.  

---

💡 *Tip: When practicing these, speak out loud as if you’re presenting to a non-technical exec or sysadmin. Focus on outcomes (availability, security, cost savings), not just technical features.*


---
## By the End

✔ 5 portfolio projects (each with IaC, diagrams, READMEs)  
✔ 5 blog/LinkedIn posts documenting architect-level designs  
✔ AZ-305 certification badge  

> 💡 This plan ensures you not only **pass the exam** but also showcase a **consultant-ready portfolio** of real-world Azure architectures.
