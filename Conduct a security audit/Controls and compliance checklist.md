### Activity Overview
This activity focuses on assessing the **security controls** and **compliance posture** of Botium Toys, a fictional company. The purpose is to identify missing safeguards, evaluate adherence to compliance frameworks (PCI DSS, GDPR, SOC), and recommend improvements to enhance the company’s overall cybersecurity maturity and resilience.
The assessment was conducted based on the **scope, goals, and risk report** as well as the **control categories** defined in the course materials.


## Scope and Goals
**Scope:**  
The assessment covered Botium Toys’ entire security program, including:
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



## Control Categories

| Category | Examples | Purpose |
|-----------|-----------|----------|
| **Administrative / Managerial** | Policies, procedures, least privilege, separation of duties, disaster recovery plan | Define responsibilities and ensure data is managed securely |
| **Technical** | Firewalls, IDS, antivirus, encryption, password management | Protect systems and detect/respond to threats |
| **Physical / Operational** | Locks, CCTV, fire alarms, badge readers | Prevent unauthorized physical access to assets |

**Control Types:**  
- **Preventative:** Stop incidents (e.g., firewalls, access control)  
- **Detective:** Identify incidents (e.g., IDS, CCTV)  
- **Corrective:** Recover from incidents (e.g., backups, recovery plans)  
- **Deterrent:** Discourage attacks (e.g., signage, visible surveillance):contentReference[oaicite:3]{index=3}



## Controls Assessment Checklist

| Control | Status |
|----------|--------|
| Least Privilege | ❌ No |
| Disaster Recovery Plan | ❌ No |
| Password Policies | ✅ Yes (but weak) |
| Separation of Duties | ❌ No |
| Firewall | ✅ Yes |
| Intrusion Detection System (IDS) | ❌ No |
| Backups | ❌ No |
| Antivirus Software | ✅ Yes |
| Manual Maintenance (Legacy Systems) | ❌ No |
| Encryption | ❌ No |
| Password Management System | ❌ No |
| Locks (Offices/Warehouse) | ✅ Yes |
| CCTV Surveillance | ✅ Yes |
| Fire Detection / Prevention | ✅ Yes |



## Compliance Checklist

### PCI DSS
| Best Practice | Status |
|----------------|--------|
| Only authorized users access card data | ❌ No |
| Credit card data stored securely | ❌ No |
| Data encryption implemented | ❌ No |
| Secure password management | ❌ No |

### GDPR
| Best Practice | Status |
|----------------|--------|
| EU customer data kept private | ❌ No |
| Breach notification plan (72 hr) | ✅ Yes |
| Data classification and inventory | ❌ No |
| Privacy policies enforced | ✅ Yes |

### SOC Type 1 / 2
| Best Practice | Status |
|----------------|--------|
| User access policies established | ❌ No |
| Sensitive data kept confidential | ❌ No |
| Data integrity ensured | ✅ Yes |
| Authorized data access enforced | ✅ Yes |



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




