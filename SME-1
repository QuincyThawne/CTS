## 10:16 AM 18-03-2025

### Karthick - GenZ leader (25 yr exp) and CSP

#### Cybersecurity Controls:
- GRC
- Threat and vulnerability management
- Data Protection & management
- Identity and Access Management
- Cloud & Infra Security

Omni channel?

### Sivakumar Swaminathan - SAST/DAST

#### Vulnerability Management:

**Phase 1**
- What is vulnerability
- The need for vulnerability management
- Vulnerability, threat, and risk
- CIA triad
- Types of vulnerabilities

**Vulnerability:**
A vulnerability is a weakness or flaw in a system, application, or network that attackers can exploit to gain unauthorized access or control.

**Key areas of vulnerability management:**
- Protects sensitive data
- Reduces risk
- Ensures compliance
- Maintains system integrity
- Prevents financial loss
- Enhances reputation
- Improves incident response
- Supports business continuity
- Facilitates proactive security
- Adapts to evolving threats

**Honeypot:**
A network that is hosted by an organization to attract attackers and is exposed to the internet.

**Types of Vulnerabilities:**
- Software vulnerabilities
- Network vulnerabilities
- Misconfigurations
- Unsecured APIs
- Outdated or unpatched software
- Access control issues
- Zero-Day
- Human error

**P.S:** HDFC Bank is not safe (every vulnerability was explained with HDFC Bank as an example)

**Phase 2**

- Vulnerability management lifecycle
- Basics of vulnerability assessment methodologies
- Vulnerability management workflow
- Common vulnerability scanning tools
- Brief about vulnerability management

#### Vulnerability Management Lifecycle:
- Discover assets
- Assess the vulnerability and assets
- Prioritize the assets and risk
- Report the findings to stakeholders
- Remediate the assets from the risk of exploitation
- Verify the remediation was successful (false positives)

**Types of assets:**
- Internet-facing assets (higher priority)
- Internal-facing assets (lower priority)

**CVSS (assign a rank to the vulnerability and prioritize it):**
- 5 is the highest score
- 4 is the high-level vulnerability
- 3 is the medium-level vulnerability
- 2,1 are low-level vulnerabilities

#### Vulnerability Management Workflow:
- Planning and preparation
- Information gathering
- Vulnerability identification
- Vulnerability analysis
- Risk assessment
- Reporting

**Scanning Methodologies:**
- Remote Scanning (using IPs)
- Agent-Based Scanning (software planted such as Anti-Virus)
- Credential-Based Scanning (authenticated scan to reduce false positives)
- Non-Credential-Based Scanning (black-box testing with no authenticity or public accessibility)
- Passive Scanning
- Active Scanning
- Internal Scanning (conducted from within the network)
- External Scanning (conducted from outside the network)
- Network Mapping
- Port Scanning

### Pen-Testing:
Penetration testing is a simulated attack against your computer system or web servers to check for exploitable vulnerabilities.

**PT Classification:**
- White box (given the entire configuration, code, architecture, and credentials to conduct the PT)
- Black box (little to no information given for testing, e.g., only IP or URL)
- Grey box (combination of both)

**Different ways of testing:**
- Automated Penetration Testing
- Manual Penetration Testing

**Phases:**
- Setup - create sandbox and configure tools
- Discovery - identify target
- Enumeration - scan
- Detection - identify and assess
- Exploitation - use the exploit
- Post-exploitation - assess the damage
- Reporting - report the above results
- Readout - present the report
- Remediation - fix any and all exploits
- Final testing - do it all over again

### Audit, VA, and PT:
- Security audits ensure governance and compliance in an enterprise
- Vulnerability assessment
- Penetration testing

#### Benefits of VAPT:
- Proactive mitigation
- Assurance
- Achieve compliance
- Evaluate the efficiency of the network
- Reduce impact

### Common Ports:
- 135, 445 - Windows
- 137, 139
- 22

**Qualys - Lab**

---

### Siva - DAST/SAST

#### DAST (Dynamic Application Security Testing):
- Tests are done without access to source code.
- Identifies issues in runtime.
- Done by simulated testing.
- Can be either black-box or grey-box.

**DAST Process (Grey-Box):**
1. Application profiling (collect data from the dev team such as URLs)
2. Automated scan (use tools such as vulnerability scan)
3. Analyze false positives (filter false positives)
4. Manual testing (find false positives and false negatives)
5. Reporting (inform stakeholders)
6. Remediation (aid devs to fix the vulnerabilities)
7. Rescan and closure (repeat the process)

#### Web Application Vulnerabilities:

**Logical Vulnerabilities (Detected by Human Errors):**
- Business logic, race conditions, input validation, etc.
- Transaction logic flaws
- Session management issues
- Error handling problems
- Unintended functionalities

**Technical Vulnerabilities (Detected by Tools):**
- Injection attacks, SSRF, CSRF (Found in OWASP Top 10)

**DAST Tools:**
- OWASP ZAP, Burp Suite, Veracode, Microfocus
- Tool scans web applications for vulnerabilities

### SAST & SCA:

**SAST (Static Application Security Testing):**
- Tests are done with access to source code.
- Done by simulated testing.
- It is white-box testing.
- It has to be automated.

**SAST Methodology:**
1. Source code with associated libraries
2. Compile the source code using IDE and import it for automated scanning
3. Tool reports security issues in a dashboard
4. Analyze issues, eliminate false positives, benchmark with OWASP Top 9
5. Report walkthrough sessions with dev teams on remediation
6. Iterative rescan of fixed code

#### OWASP Top 9:
- Input validation
- Insecure code design
- Information leakage and error handling
- Direct object reference
- Insecure file creation
- Insecure database calls
- Variable aliasing
- Weak session management
- Using HTTP GET query strings

**SQL Injections:**
- Tautologies (e.g., `OR 1=1`)
- UNION Queries (number of columns in the first query)

**Prevention:**
- Prepared statements and input validation
- Least privilege
- Whitelist input validation

### SCA (Software Composition Analysis):
- Inspects software components and dependencies.
- Identifies vulnerabilities and compliance concerns.
- Analyzes dependency graphs for risk assessment.

**SCA Tools:**
- OWASP Dependency-Check
- SpotBugs
- DevSkim
- SonarQube
- Snyk

### SDLC Comparison:
| Aspect  | SAST  | DAST  | SCA  |
|---------|-------|-------|------|
| Phase  | Early (Coding, Build)  | Late (Testing, Staging, Production)  | Throughout SDLC  |
| Focus  | Application code  | Running application behavior  | Third-party libraries  |
| Requires  | Source code  | Running application  | Dependency info  |
| Detects  | Code flaws  | Runtime vulnerabilities  | Known vulnerabilities  |
| Advantages  | Early detection  | Real-world perspective  | License management  |
