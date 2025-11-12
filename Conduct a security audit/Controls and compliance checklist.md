## Activity Overview
This activity focuses on assessing the **security controls** and **compliance posture** of Botium Toys, a fictional company. The purpose is to identify missing safeguards, evaluate adherence to compliance frameworks (PCI DSS, GDPR, SOC), and recommend improvements to enhance the company’s overall cybersecurity maturity and resilience.
The assessment was conducted based on the **scope, goals, and risk report** as well as the **control categories** defined in the course materials.


## Scope and Goals

**Scope:**  
- All IT-managed assets  
- Internal processes and procedures  
- Compliance and regulatory alignment  

**Goals:**  
- Identify which controls are currently implemented  
- Evaluate compliance with PCI DSS, GDPR, and SOC frameworks  
- Recommend key improvements to strengthen data protection and risk management  



## Risk Assessment Summary
| Category | Description |
|-----------|-------------|
| **Risk Score** | 8 / 10 — High risk due to inadequate controls and incomplete compliance |
| **Main Risks Identified** | Lack of encryption, missing IDS, no disaster recovery or backup system |
| **Impact** | Potential for data breaches, regulatory fines, and operational downtime |
| **Current Strengths** | Firewall in place, antivirus monitored, CCTV & fire detection systems active |
| **Weaknesses** | Weak password policy, lack of least privilege access, no centralized password management, unmaintained legacy systems |



## Controls Assessment Checklist

| Control | Status |
|----------|--------|
| Least Privilege | ❌ No |
| Disaster Recovery Plans | ❌ No |
| Password Policies | ✅ Yes (but weak) |
| Separation of Duties | ❌ No |
| Firewall | ✅ Yes |
| Intrusion Detection System (IDS) | ❌ No |
| Backups | ❌ No |
| Antivirus Software | ✅ Yes |
| Manual monitoring, maintenance, and intervention for legacy systems | ❌ No |
| Encryption | ❌ No |
| Password Management System | ❌ No |
| Locks (offices, storefront, warehouse) | ✅ Yes |
| Closed-circuit television (CCTV) surveillance | ✅ Yes |
|Fire detection/prevention (fire alarm, sprinkler system, etc.) | ✅ Yes |



## Compliance Checklist

### Payment Card Industry Data Security Standard (PCI DSS)
| Best Practice | Status |
|----------------|--------|
| Only authorized users have access to customers’ credit card information | ❌ No |
| Credit card information is stored, accepted, processed, and transmitted internally, in a secure environment | ❌ No |
| Implement data encryption procedures to better secure credit card transaction touchpoints and data | ❌ No |
| Adopt secure password management policies. | ❌ No |

### General Data Protection Regulation (GDPR)
| Best Practice | Status |
|----------------|--------|
| E.U. customers’ data is kept private/secured | ❌ No |
| There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach | ✅ Yes |
| Ensure data is properly classified and inventoried | ❌ No |
| Enforce privacy policies, procedures, and processes to properly document and maintain data | ✅ Yes |

### System and Organizations Controls (SOC type 1, SOC type 2) 
| Best Practice | Status |
|----------------|--------|
| User access policies are established | ❌ No |
| Sensitive data (PII/SPII) is confidential/private | ❌ No |
| Data integrity ensures the data is consistent, complete, accurate, and has been validated | ✅ Yes |
| Data is available to individuals authorized to access it | ❌ No |



##  Recommendations

### 1. Enhance Data Security and Compliance
- Implement **data encryption** for customer payment and personal data.  
- Enforce **least privilege** and strong **user access policies**.  
- Deploy a **centralized password management system** and enforce complex password standards.  

### 2. Improve Threat Detection and Recovery
- Install an **Intrusion Detection System (IDS)**.  
- Create a **disaster recovery plan** and **perform regular backups**.  
- Establish a **maintenance schedule** for legacy systems.  

### 3. Strengthen Compliance and Documentation
- **Classify and inventory** data assets for GDPR.  
- Regularly review and **update privacy policies**.  
- Conduct **internal audits** to verify control effectiveness.  






