# Controls and compliance checklist

**Controls assessment checklist**

|   Yes |     No | Control |
| ----- | ----- | :---- |
|  | x | Least Privilege |
|  | x | Disaster recovery plans |
| x |  | Password policies |
|  | x | Separation of duties |
| x |  | Firewall |
|  | x | Intrusion detection system (IDS) |
|  | x | Backups |
| x |  | Antivirus software |
|  | x | Manual monitoring, maintenance, and intervention for legacy systems |
|  | x | Encryption |
|  | x | Password management system |
| x |  | Locks (offices, storefront, warehouse) |
| x |  | Closed-circuit television (CCTV) surveillance |
| x |  | Fire detection/prevention (fire alarm, sprinkler system, etc.) |

---

**Compliance checklist**

Payment Card Industry Data Security Standard (PCI DSS)

| Yes |     No | Best practice |
| ----- | ----- | :---- |
|  | x | Only authorized users have access to customers’ credit card information.  |
|  | x | Credit card information is stored, accepted, processed, and transmitted internally, in a secure environment. |
|  | x | Implement data encryption procedures to better secure credit card transaction touchpoints and data.  |
|  | x | Adopt secure password management policies. |

General Data Protection Regulation (GDPR)

| Yes |     No | Best practice |
| ----- | ----- | :---- |
|  | x | E.U. customers’ data is kept private/secured. |
| x |  | There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach. |
| x |  | Ensure data is properly classified and inventoried. |
| x |  | Enforce privacy policies, procedures, and processes to properly document and maintain data. |

System and Organizations Controls (SOC type 1, SOC type 2\) 

| Yes |     No | Best practice |
| ----- | ----- | :---- |
|  | x | User access policies are established. |
|  | x | Sensitive data (PII/SPII) is confidential/private. |
|  | x | Data integrity ensures the data is consistent, complete, accurate, and has been validated. |
|  | x | Data is available to individuals authorized to access it. |

---

| Finding | Risk | Impact | Recommendations | Categories |
| :---- | :---- | :---- | :---- | :---- |
| Sensitive data is not encrypted | In the event of a data breach, this could have a high impact on confidentiality and integrity. | High | Implement encryption mechanism to protect sensitive data from unauthorized access | Deterrent |
| No backup system is implemented in place | In the event of a ransomware attack, this could result in significant data loss, extended downtime, and a high impact on availability, integrity, and confidentiality.  | High | Implement backup and recovery systems to protect data and ensure business continuity | Corrective |
| Excessive privileges were identified in a standard user account | If the account is compromised, excessive privileges to confidential data have a high impact on a data breach. | High | Implement a principle of least privilege to ensure employees only have a minimum level of access necessary for the functions of their role. | Preventive |
| No disaster recovery plans in place | In event of a database compromise, this could have a high impact on availability and business continuity | High | Implement a disaster recovery plans to ensure business continuity | Corrective |
| Multiple critical functions were assigned to a single employee | Assigning multiple critical tasks to a single employee could have a high impact on the integrity of assets, in the event of a compromise. | High | Implement separation of duties (SoD) as an administrative control to ensure critical tasks are distributed among multiple employees | Preventive |
| The organization does not comply with applicable regulations and government laws | If the organization does not comply, this could result in financial loss, reputational damage, legal penalties, and operational disruption. | High | Ensure compliance with applicable laws and regulations.  | Governance |
| Password policies aren’t clearly defined. | In the event of a compromise, the use of weak passwords could have a high impact on confidentiality and integrity, compromising employee accounts, creating a risk to the organization's data and assets.  | Medium | Implement password policies to protect the confidentiality and integrity of accounts  | Preventive |
| No password management system is in place | If a password management system is not in place, this could lead to credential exposure, unauthorized access, and poor security practices. | Medium | Implement a password management system to protect and manage the employee credentials | Preventive |

