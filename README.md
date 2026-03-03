
# 📊 BotiumToys-IT-Audit

## Overview
Botium Toys is a small U.S. business that develops and sells toys through a physical storefront and an expanding online presence. As the company grows, its IT department faces increasing pressure to secure infrastructure, ensure compliance, and support global operations.  

This repository contains the **internal IT audit project** for Botium Toys, including:
- Scope and goals of the audit  
- Risk assessment findings  
- Controls and compliance checklist (Administrative, Technical, Physical/Operational)  
- Recommendations for improving security posture and regulatory compliance  

---

## Audit Scope
- Entire IT infrastructure (office, storefront, warehouse, online systems).  
- Employee devices, internal network, and cloud services.  
- Payment processing systems and customer data (U.S. and E.U.).  
- Compliance with **PCI DSS**, **GDPR**, and **SOC 1 & 2**.  

---

## Goals
- Identify risks, threats, and vulnerabilities to critical assets.  
- Ensure compliance with U.S. and E.U. regulations.  
- Provide an overview of potential risks and fines.  
- Recommend controls to strengthen security posture.  

---

## Assets Reviewed
- Physical servers and local network.  
- Website/e-commerce platform.  
- Customer data (PII/SPII, cardholder data).  
- Payment systems.  
- Employee devices/accounts.  
- Legacy systems requiring manual monitoring.  

---

## Risk Assessment Summary
- **Risk Score**: 8/10 (High).  
- **Key Risks**: Data breaches, compliance fines, downtime, insider threats, weak access controls.  
- **Impact**: High for regulatory fines, medium for asset loss.  

---

## Controls & Compliance Checklist
### Administrative/Managerial
- Least Privilege → ❌ Missing  
- Disaster Recovery Plan → ❌ Missing  
- Password Policies → ⚠️ Weak  
- Separation of Duties → ❌ Missing  

### Technical
- Firewall → ✅ Implemented  
- IDS/IPS → ❌ Missing  
- Encryption → ❌ Missing  
- Backups → ❌ Missing  
- Antivirus → ✅ Implemented  
- Password Management → ❌ Missing  
- Legacy System Monitoring → ⚠️ Partial  

### Physical/Operational
- Locks, CCTV, Fire Detection → ✅ Strong  

---

## Compliance Status
- **PCI DSS** → ❌ Major gaps (encryption, access control, backups).  
- **GDPR** → ⚠️ Partial (breach notification plan exists, but data classification/encryption missing).  
- **SOC 1 & 2** → ⚠️ Partial (confidentiality/integrity controls incomplete).  

---

## Recommendations
1. Encrypt cardholder and customer data immediately.  
2. Implement least privilege and separation of duties.  
3. Deploy IDS/IPS for network monitoring.  
4. Establish disaster recovery and backup plans.  
5. Strengthen password policies and enforce via centralized management.  
6. Formalize legacy system maintenance schedules.  

---

## Repository Structure
```
BotiumToys-IT-Audit/
│
├── README.md                # Project overview
├── Scope_Goals.pdf          # Audit scope and goals
├── Risk_Assessment.pdf      # Detailed risk assessment
├── Controls_Checklist.pdf   # Controls & compliance checklist
└── Recommendations.pdf      # Priority recommendations
```

  

Would you like me to also design a **visual compliance matrix (red/yellow/green table)** as a PDF so you can include it in the repo as a quick reference for stakeholders?
