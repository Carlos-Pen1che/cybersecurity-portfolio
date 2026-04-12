# Security Incident Report: Phishing attack

## Summary
A phishing attack targeted a trainee employee of a small company. The employee interacted with a suspicious email, potentially leading to credentials compromise.

## Incident Details
- **Date:** 2026-04-12
- **Affected Systems:** Employee email account
- **Threat Type:** Phishing
- **Severity Level:** Medium - Potential credential compromise

## Detection
The incident was detected using SIEM tools, which identified a login attempt from an unauthorized IP address on the employee's email account

## Indicators of Compromise (IOCs)
- Suspicious email: verification@company-supp0rt.com
- Suspicious domain: company-login-verificati0n.ru
- Unauthorized IP: 154.124.23.45

## Analysis
The attack ocurred because an employee interacted with a suspicios email.  This was likely due to a lack of knowledge about phishing, the threat actor exploited social engineering techniques such as urgency and possibly authority

## Impact Assessment (CIA Triad)
- **Confidentiality:** High Impact - Potencial credentials compromise could expose sensitive information.
- **Integrity:** Pontencially High Impact - The threat actor modify or steal a important company data.
- **Availability:** Low Impact - There is no evidence of disruption, but a potencial risk exists if malware such as ransomware is introduced.

## Response Actions
Follow the incident response procedures in a company, including blocking suspicious IP adress, analyzing potential malware introduced, resetting compromised credentials, reporting the incident, after monitoring for further suspicious activity.

## Recommendations
Implement Multi-Factor Authentication (MFA) on all accounts.
Provide employee training on phishing awareness.
Deploy email filtering solutions to detect malicious messages.