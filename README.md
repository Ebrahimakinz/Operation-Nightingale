<h1>Cybersecurity Incident Management</h1>

## Operation Nightingale Incident Response Simulation

### Project Context:

Following the tactical profiling of APT29, this project captures the high-pressure transition from threat intelligence to Active Incident Response; a comprehensive response to Operation Nightingale, a sophisticated campaign targeting healthcare and pharmaceutical entities. The objective was to manage the lifecycle of a breach—moving from technical root-cause analysis to executive risk communication and legal regulatory compliance. <br />
This project simulates the end-to-end responsibilities of a Threat Intelligence Analyst and Incident Response Lead, bridging the gap between deep technical analysis and executive-level governance, culminating in a simulated breach response that addressed legal, financial, and operational requirements.


<br />
<p align="center">
 Incident Response & Crisis Governance
<br/>
<img src="https://imgur.com/0umVoA9.png" height="80%" width="80%" alt="Incident Response"/>
<br />
</p>
### Operation Nightingale Post-Mortem:

<br/>
<p align="center">
Analysis Workbook<br />
The technical foundation of the investigation. We reconstructed a minute-by-minute timeline of the breach and compiled a comprehensive registry of Indicators of Compromise (IOCs) to facilitate threat hunting and prevent re-entry. <br />

<img src="https://imgur.com/OJnLjCq.png" height="80%" width="80%" alt="Analysis"/>
<img src="https://imgur.com/BO8sNIQ.png" height="80%" width="80%" alt="Analysis"/><br />
<P/>
Root Cause & Containment Memo : <br />


On May 16th, 2025, an attacker successfully compromised the account radiotech1@oh.ca using a malicious OAuth app that bypassed MFA, granting access to Microsoft 365 services. PowerShell-based malware executed on RADIOLOGY-VDI-23 initiated credential theft and exfiltrated approximately 2.2 GB of sensitive data. The Security Operations Center (SOC) responded by isolating the affected endpoint and blocking the exfiltration IP.
<br/>
<p align="center">
Summary<br />
A formal briefing for the Director of IT Security detailing the attack vector, root cause analysis, and a summary of the immediate containment actions taken to neutralize the threat. <br />
<img src="https://imgur.com/xN2NjLZ.png" height="80%" width="80%" alt="Incident Response"/><br />
<img src="https://imgur.com/X3tUfcZ.png" height="80%" width="80%" alt="Incident Response"/>
<br />
Decision Log<br />
An audit-ready record of the "Golden Hour" response. For every critical action, We documented the alternative options considered, the final choice made, the underlying rationale, and the designated decision-maker to ensure total accountability. <br />
<img src="https://imgur.com/sLadRYO.png" height="80%" width="80%" alt="Decision Log"/><br />
<img src="https://imgur.com/GjFjBvG.png" height="80%" width="80%" alt="Decision Log"/>
<img src="https://imgur.com/Q5iiORl.png" height="80%" width="80%" alt="Decision Log"/><br />
<img src="https://imgur.com/aLOPqlz.png" height="80%" width="80%" alt="Decision Log"/><br />
Regulatory Letter<br />
A formal draft letter to the Information and Privacy Commissioner of Ontario (IPC). Prepared under the requirements of PHIPA s.12(3), this legal document provides the precise, factual disclosure required for a notifiable breach involving sensitive health data. <br />
<img src="https://imgur.com/Nc0LYRY.png" height="80%" width="80%" alt="Regulatory Letter"/><br />
<img src="https://imgur.com/L366qF1.png" height="80%" width="80%" alt="Regulatory Letter"/>
<br />
Public Statement & Employee FAQ<br />
A concise, transparent media release (≤ 300 words) designed to maintain public trust while managing reputational risk.<br />
<img src="https://imgur.com/F46iSKM.png" height="80%" width="80%" alt="Public Statement"/><br />
A one-page internal guide distributed to employees to ensure consistent messaging, clarity on data safety, and guidance on operational continuity during the recovery phase <br />
<img src="https://imgur.com/EfbAjSw.png" height="80%" width="80%" alt="Internal Employee"/>
<br /> 
Lessons Learned<br />
<img src="https://imgur.com/TKGYQki.png" height="80%" width="80%" alt="Public Statement"/><br />
<p/>

 
#### FINAL EXECUTIVE BRIEFING:
A high-level presentation designed for non-technical executives. We translated technical forensic data into Business Impact, provided high-level financial damage estimates, and proposed a tiered Strategic Recovery Roadmap. 

<p align="center">
Executive Summary: <br/>
<img src="https://imgur.com/IQvnfEn.png" height="80%" width="80%" alt="Exec Summary"/>
<br />
<br />
Business Impact: <br/>
<img src="https://imgur.com/iH2oRbh.png" height="80%" width="80%" alt="Exec Summary"/>
<br />
<br />
High Level Financial Estimate: <br/>
<img src="https://imgur.com/2xozFTg.png" height="80%" width="80%" alt="Exec Summary"/>
<br />
<br />
Root Cause Overview: <br/>
<img src="https://imgur.com/NFloRjW.png" height="80%" width="80%" alt="Exec Summary"/>
<br />
<br />
Strategic Recovery roadmap: <br/>
<img src="https://imgur.com/ZfWZeKo.png" height="80%" width="80%" alt="Exec Summary"/>
<br />
<br />
Recommendations to Leadership: <br/>
<img src="https://imgur.com/Neex6j0.png" height="80%" width="80%" alt="Exec Summary"/>
<br />
<br />
</p>

By balancing the need for technical forensics with legal obligations and clear public communication, we ensured that the response is not just a 'recovery,' but a demonstration of organizational resilience and integrity."

