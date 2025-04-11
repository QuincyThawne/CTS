09:56 AM 04-04-2025

Chandrasekaran - senior project manager in cognizant and 21+ years

Vignesh - Cyber security specialist and 14+ years in the industry


FACTS:
- Every month the second Tuesday Microsoft releases patches
- ATTACK VECTOR is identified for Anti-Virus Apps
- EDR (End-Point Detection and Response) will use AI for identifying Virus and malware
- CROWN JEWEL APPLICATION is the most critical asset of the organization
- HIPPA : GRC framework for healthcare 
- BYoD : Bring your own Device
- CISO : Chief Information Security Officer, is a senior-level executive responsible for establishing and maintaining an organization's information security strategy and program, ensuring the protection of its assets and data
- CIO : Chief Information Officer, a key executive role responsible for overseeing an organization's information technology (IT) strategy and implementation, ensuring it aligns with business goals and drives digital transformation. 
- CEO : final decision maker after CISO->CIO->CEO to take a decision considering the finance, budget and effects for the causes
- Playbook : a structured, pre-defined set of procedures and guidelines that organizations use to handle various cybersecurity incidents and threats, ensuring a swift and effective response. 
- Mossad : Biggest intelligence in the world which belongs to israel
- UEBA : User and Entity Behavior Analytics, is a cybersecurity approach that uses machine learning and behavioral analytics to detect anomalies in user and entity (like servers, firewalls, and databases) behavior, helping identify potential threats, including insider threats and cyberattacks. 
- EMAIL Security Protocols : SPF, DKIM, DMARC
- KPI : key performance indicators

Agenda:
- security triad
- defense in depth
- key cybersecurity practice
- CNI overview
- firewall and WAF
- proxy and VPN
- endpoint and email security
- SIEM and SOC
- cloud basics and security
- IRIL


5 categories
- IAM (MFA, single sign on, passwords)
- Data protection and Privacy (encryption, data masking, DLP)
- CNI (cloud Infra and Network security, web-app, email)
- GRC 
- Threat and Vulnerability management 


Definition:
	Cybersecurity is the body of technologies, processes and practices designed to protect networks, computers, programs and data from attack, damage or unauthorized access.

- Confidentiality: protect info from unauthorized disclosure
- Integrity: Protecting information from being modified by an unauthorized party.
- Availability: Ensuring information is available to authorized parties when needed.


DEFENCE IN DEPTH:

- Policies, procedures and awareness : passwords, policies and data classification  
  *For Instance:* most organizations conduct mock tests to their employees without them knowing such as sending a phishing mail to see if they fall victim for it.

- Physical: locks, fences and security guards  
  *For Instance:* organizations have standards for the fences and authentication mechanisms such as having multiple biometrics despite a physical access card.

- Perimeter: firewall, VPN and packet filters  
  *For Instance:* DMZ zones are used for filtering internal network and public network

- Internal Network : Firewall, instruction detection and encryption  
  *For Instance:* DMZ example

- Host: Platform OS, patches and malware protection  
  *For Instance:* your devices should have patches up to date so that you can be protected

- App : SSO, authentication and authorization

- Data : Database, content and message security


KEY CYBERSECURITY PRACTICES:
- IDAM (Identity and Access Management)
- CNI (Cloud, Network and Infra Security)
- TVM (Threat and Vulnerability Management)
- GRC (Governance, Risk and Compliance)
- DPP (data protection and privacy)


DoS and DDoS:
- DoS: a single source attack, easier to block
- DDoS: multiple source attacks, harder to defend


---

## CLOUD, NETWORK & INFRA SECURITY OVERVIEW

### Cloud Security
- App on Cloud - CSPM
- Hybrid/ Multi Cloud - CWPP
- Cloud Migrate/Operate - Iaas/PaaS/Saas

### Network Security
- Network Protect - Firewall
- Access Protect - NAC
- Web Protect - Proxy
- Policy * Platform App - Intrusion

### Infra Security
- Host Protect - Malware
- Email Protect - Emails
- Micro segmentation - Zero Trust
- FIM - Unauthorized Access

**SIEM/ SOARI/ Threat Intel/ Threat Hunting/ UEBA**
- Monitoring, IR, Orchestration & Automation
  - Threat Management

### ENABLERS:
- Control assessment
- Automation & orchestration
- AI/ML
- Ticketing tool
- Delivery Excellence

### Acronyms:
- CSPM - Cloud Security Posture Management
- CWPP - Cloud Workload Platform Protection
- SIEM - Security Information and Event Management
- CASB - Cloud Access Security Broker
- UEBA - User Entity Behavior Analysis
- SOAR - Security Orchestration and Automation and Response 
- AI - Artificial Intelligence
- ML - Machine Learning
- IoT - Internet of Things
- OT - Orchestration Tool

---

## FIREWALL AND WAF

### Firewall:
- Controls the flow of traffic into and out of a network
- Prevents attacks
- Acts as a buffer between public and private networks

**Types of Firewall**
- Packet filtering
- Circuit level gateways
- Application level gateway (proxy)
- Stateful multilayer inspection (SMLI)
- Next Gen Firewalls
- Cloud Firewalls
- Unified threat management (UTM)

**Vendors**
- Palo Alto
- Fortinet
- CISCO
- Check Point
- Barracuda
- Juniper Networks

---

### WEB APPLICATION FIREWALL (WAF):
- Defends layer 7 from malicious traffic
- Protects from OWASP top 10, zero-day threats
- Inspects and blocks malicious uploads
- Detects bots

**Vendors**
- Akamai 
- Barracuda
- Fortinet
- f5 (market lead)
- Cloudflare
- Imperva

---

## PROXY

**Types:**
- Forward Proxy: handles internal network requests
- Reverse Proxy: sits in front of web servers

**Deployment:**
- On-prem proxy
- Cloud proxy

**Vendors:**
- Microsoft
- Zscaler
- Forcepoint
- Broadcom

---

## VPN
- Secure, encrypted connection
- Common types:
  - Site to Site
  - Remote Access
  - Cloud VPN
  - SSL VPN

---

## ANTIVIRUS ACTIONS:
- Delete
- Quarantine
- Clean
- Pass
- Deny Access

**States of Data:**
- In use
- In transit
- At rest

**DLP:**
- Data Discovery
- Data Classification
- Data Protection

---

## WHITELISTING
- Only allows trusted sources (email, IP, apps)
- Trust centric approach

---

## EMAIL SECURITY:
- DMARC, DKIM, SPF for authentication and anti-spam

**Vendors:**
- Broadcam
- Cisco
- Crowdstrike
- Forcepoint
- Microsoft
- Proofpoint
- SentinelOne
- Trend Micro
- Trellix

---

## SOC - SECURITY OPERATION CENTER

Central team that monitors and responds to cyber threats

**Roles:**
- Tier 1: Alert triage
- Tier 2: Response and Mitigation
- Tier 3: Deep Analysis, RCA
- Incident Response Coordination
- Threat Intelligence Analyst
- Threat Hunter
- Security Engineer

**SIEM Frameworks:**
- MITRE ATT&CK
- NIST

**Vendors:**
- Crowdstrike
- IBM Radas
- Cisco
- Trellix
- SolarWinds
- Fortinet
- Microsoft
- ManageEngine

---

## CLOUD VENDORS:
- Microsoft
- AWS
- Google
- Oracle

---

## ITIL

**Key Areas:**
- Service strategy
- Service design
- Service transition
- Service operation
- Continual service improvement

**Operations:**
- Incident management
- Change management
- Problem management
- Capacity management

**Motto:** 10% technical skills - 90% process following

---

fortigate.fortidemo.com/  
username: demo  
password: demo
