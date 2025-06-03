# univiersity-Financial-Portal-threat-model
🔐 AAST Financial Portal – Threat Modeling
This project repository contains the threat modeling documentation for the AAST Financial Portal, covering system architecture, threat analysis, and vulnerability trees.

📁 Project Contents
File	Description
THREAT MODELING REPORT.htm	Comprehensive report detailing the system architecture, user roles, protocols, assets, and implemented mitigations.
ATTACK TREE.pdf	Visual representation of a detailed attack tree focused on weak authentication mechanisms and brute-force attack susceptibility.
project_threatmodel.tm7	Microsoft Threat Modeling Tool project file containing structured threat model elements and diagrams.

🛡️ Project Overview
The AAST Financial Portal is a secure platform designed to support users such as students, staff, administrators, and remote employees. It emphasizes:

Role-based access control

Encrypted communication (HTTPS, VPN, IPsec, SFTP)

Multi-directory authentication (internal & DMZ-based Active Directory)

Monitoring and backup operations in restricted zones

🧠 Threat Modeling Approach
We applied Microsoft’s STRIDE methodology and included:

Detailed architecture diagram

Identification of threats across different user roles and system components

Mitigation tracking and status

A formal attack tree (PDF)

📌 Key Threat Categories
Weak Authentication

Insecure fallback protocols

Easily guessable passwords

Missing CAPTCHA/rate-limiting

Poor credential lifecycle management

Remote Access Risks

VPN vulnerabilities

Student-facing AD in DMZ

External device reliance

Data Transmission & Storage

Sensitive data over insecure protocols

Weak encryption

Insufficient backup segregation

🧰 Tools Used
Microsoft Threat Modeling Tool (.tm7)

Draw.io / Manual Diagrams (PDF Attack Tree)

Custom HTML reports for structured documentation

📜 License
This project is protected under the appropriate academic or institutional guidelines. Usage is limited to educational or assessment purposes.

