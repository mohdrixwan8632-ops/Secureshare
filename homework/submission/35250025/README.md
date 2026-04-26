## 1. Security Maturity Assessment

Based on the provided information, GreenFields has a *low cybersecurity maturity level*. Security practices are mostly informal and unstructured.

There are no defined security policies or procedures, and no formal risk assessment has been done. This means the company does not fully understand its risks or how to manage them.

Several critical weaknesses are visible:
- Shared administrator passwords increase risk of misuse
- No monitoring systems are there to detect threats
- No incident response plan exists, meaning the company is not prepared for attacks
- Employees are not trained in cybersecurity awareness

Considering the recent incidents (phishing, ransomware at supplier, lost laptop), the organization is highly exposed to cyber threats and cannot respond effectively.

## 2. Top 10 Security Risks

1. *Lack of network segmentation*  
   Attackers can freely have access between production and corporate systems.

2. *Shared administrator credentials*  
   high risk of unauthorized access.

3. *No security monitoring*  
   Attacks may remain undetected for long periods.

4. *Absence of security policies*  
   Employees do not have clear guidelines to follow.

5. *No incident response plan*  
   Delayed reaction increase more data breaches.

6. *Unpatched systems*  
   Systems remain vulnerable to known exploits.

7. *Backup stored on same network*  
   Backups can be compromised during ransomware attacks.

8. *Unprotected endpoints*  
   Lost or stolen devices can lead to data breaches.

9. *Weak VPN access controls*  
    vpn access is not strongly secured.


## 3. Priority Security Improvements

1. *Develop and implement security policies*  
   Define clear rules for password usage, access control, and data handling. This will become like a foundation for security measures .

2. *Implement network segmentation*  
   Separate production systems, office systems, and guest networks so that the attack doesnt spread between them.

3. *Eliminate shared administrator accounts*  
   Assign individual accounts with role-based access control to decrease vulnerability of threats.

4. *Enable Multi-Factor Authentication (MFA)*  
   Apply MFA especially to Microsoft 365 and VPN access so that credentials aren'nt vulnerable to attacks.

5. *Deploy endpoint protection solutions*  
   Install antivirus or EDR solutions on all laptops and servers so that it can detect malware.

6. *Establish a patch management process*  
   Schedule regular updates for operating systems and applications to reduce vulnerabilities.

7. *Improve backup strategy*  
   Store backups offline or in secure cloud storage and test the backups regularly.

8. *Introduce basic monitoring and logging*  
   Even simple centralized logging can help detect suspicious activities early.

9. *Create an incident response plan*  
   Define clear steps, roles, and responsibilities for handling security incidents.

10. *Conduct employee security awareness training*  
   Train staff to recognize phishing attacks and follow safe practices.

## 4. Implementation Roadmap (12–18 Months)

### Phase 1 (0–3 months) – Immediate Actions
- Remove shared administrator passwords  
- Enable MFA for critical systems  
- Start regular patch updates  
- Create basic security policies  
- Conduct initial employee training  

### Phase 2 (3–9 months) – Mid-Term Improvements
- introduce network segmentation  
- establish endpoint protection tools  
- Improve backup systems and test recovery  
- Strengthen VPN access controls  

### Phase 3 (9–18 months) – Long-Term Improvements
- establishing centralized monitoring (SIEM or logging system)  
- Test and refine incident response plan  
- Perform regular risk assessments  
- improving security practices constantly

## 5. Estimated Budget Allocation (€80,000/year)

- Security tools (MFA, endpoint protection, monitoring): €30,000  
- Infrastructure upgrades (network segmentation, servers): €20,000  
- Backup solutions (cloud/offline storage): €10,000  
- Employee training programs: €10,000  
- External consulting and support: €10,000  

These things focuses on practical improvements that fit within budget and provide maximum risk reduction.


## 6. Metrics for Measuring Security Improvement

1. *Patch compliance rate (%)*  
   Percentage of systems updated on time.

2. *Number of detected security incidents*  
   Helps track improvements in detection and prevention.

3. *Phishing test success rate (%)*  
   Measures employee awareness and training effectiveness.

4. *Backup success and recovery rate (%)*  
   Ensures data can be restored when needed.

5. *Mean time to detect and respond (MTTD/MTTR)*  
   It Measures how quickly incidents are identified and handled.
