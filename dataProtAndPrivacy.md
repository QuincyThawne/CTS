### DATA PROTECTION AND PRIVACY
---

### 🛡️ **Data Protection & Privacy**  
**Definition**:  
The practice of securing sensitive data from unauthorized access or misuse, while ensuring individuals’ privacy rights.  
It involves encryption, access control, and compliance with laws like GDPR and HIPAA.  
Focuses on data at rest, in transit, and in use.  
Drives both technical and legal frameworks for data security.

**Key Takeaways**:  
- Use encryption (AES, TLS) for protection.  
- Ensure compliance with regulations (GDPR, CCPA).  
- Data must be protected across all states: rest, transit, use.  
- Privacy enforces rights like consent and access control.

---

### 🔐 **Cryptography – Data Protection**  
**Definition**:  
Secures data through algorithms that transform it into unreadable formats.  
Includes encryption, decryption, hashing, and digital signatures.  
Used to protect confidentiality, integrity, and authentication.  
Two main types: symmetric (same key) and asymmetric (public/private key).

**Key Takeaways**:  
- **AES** for symmetric encryption, **RSA/ECC** for asymmetric.  
- **Hashing** (e.g., SHA-256) for data integrity.  
- TLS uses both symmetric & asymmetric encryption.  
- Foundation for secure communication and data storage.

---

### 🔍 **Data Discovery & Classification**  
**Definition**:  
Identifies where sensitive or regulated data (like PII, PCI, PHI) is stored.  
Applies classifications like confidential, internal, or public.  
Essential for risk management, compliance, and automated protection.  
Uses tools to tag, label, and act on data types.

**Key Takeaways**:  
- You can’t protect what you don’t know exists.  
- Enables policy-based controls (masking, encryption).  
- Tools: Azure Purview, AWS Macie, IBM Guardium.  
- Supports audits and regulatory requirements.

---

### 🧾 **Introduction to Public Key Infrastructure (PKI)**  
**Definition**:  
PKI uses digital certificates to secure identities and data through asymmetric encryption.  
Enables trust in digital communications and transactions.  
Operates on a trust hierarchy of Certificate Authorities (CAs).  
Core to HTTPS, email encryption, and digital signatures.

**Key Takeaways**:  
- **Public/private keys** manage identity and secure exchange.  
- Certificates issued and validated by **CAs**.  
- Supports digital signatures and encryption.  
- Enables secure authentication and trust models.

---

### 🏗️ **PKI Architecture Overview & Deployment**  
**Definition**:  
Describes the structure and components of PKI: Root CA, Intermediate CA, OCSP, CRLs, etc.  
Guides implementation for secure issuance and management of certificates.  
Addresses scalability, automation, and security (e.g., using HSMs).  
Used internally (enterprise) or externally (public trust).

**Key Takeaways**:  
- Trust hierarchy: Root → Intermediate → End Entity.  
- Certificate validation via **CRL/OCSP**.  
- Automate cert renewal with tools like Let’s Encrypt.  
- Store private keys securely with HSMs.

---

### 🔧 **OpenSSL**  
**Definition**:  
A powerful open-source toolkit for implementing SSL/TLS and performing cryptographic operations.  
Used to generate private keys, CSRs, certificates, and test secure connections.  
Widely used in web servers, VPNs, and testing environments.  
Command-line tool for security practitioners and devs.

**Key Takeaways**:  
- Generate key: `openssl genrsa -out key.pem 2048`  
- Create CSR: `openssl req -new -key key.pem -out csr.pem`  
- View cert: `openssl x509 -in cert.pem -text`  
- Essential for manual cert management and testing.

---

### 🔑 **Key Lifecycle Management Basics**  
**Definition**:  
Covers secure handling of encryption keys throughout their lifecycle: creation to destruction.  
Ensures keys are rotated, revoked, and stored properly.  
Protects against data breaches from key misuse.  
Implemented using HSMs or cloud key vaults.

**Key Takeaways**:  
- Phases: Generate → Store → Rotate → Revoke → Destroy.  
- Keys must be encrypted at rest and in transit.  
- HSMs and vaults (Azure/AWS) manage this process.  
- Automation reduces human error and enhances compliance.

---

### ☁️ **Azure Key Vault Basics**  
**Definition**:  
A cloud-based service for managing keys, secrets, and certificates in Azure securely.  
Supports role-based access and integration with Azure services.  
Automates secret rotation and versioning.  
Prevents hardcoding secrets in apps.

**Key Takeaways**:  
- Store secrets, keys, and certs securely.  
- Use RBAC and managed identities.  
- Supports logging, monitoring, and alerting.  
- Centralized control over sensitive info.

---

### ☁️ **AWS KMS Basics**  
**Definition**:  
AWS Key Management Service handles encryption key generation, storage, and use across AWS.  
Supports envelope encryption and tight integration with AWS services.  
Offers automatic key rotation and audit logs.  
Can use AWS-managed or customer-managed keys.

**Key Takeaways**:  
- Manages symmetric/asymmetric encryption keys.  
- Integrates with S3, EBS, RDS, Lambda, etc.  
- Supports access control via IAM policies.  
- Key usage is logged in AWS CloudTrail.

---

### 🕵️‍♂️ **Data Activity Monitoring (DAM)**  
**Definition**:  
Monitors who accesses what data, when, and how.  
Detects anomalous or unauthorized activity in real-time.  
Supports compliance and threat detection.  
Feeds alerts to SIEM systems.

**Key Takeaways**:  
- Tracks user actions on sensitive data.  
- Helps meet audit and compliance goals.  
- Can detect insider threats or data leaks.  
- Used across databases, file systems, and cloud apps.

---

### 🧠 **IBM Guardium – Data Activity Monitoring**  
**Definition**:  
An enterprise-grade platform for monitoring, auditing, and protecting sensitive data.  
Supports multiple DBs and platforms, on-prem and cloud.  
Provides real-time alerts, masking, and policy enforcement.  
Used to meet regulatory and security objectives.

**Key Takeaways**:  
- Tracks and logs data access events.  
- Performs vulnerability assessments.  
- Integrates with SIEM and compliance tools.  
- Enables data-centric security across hybrid environments.

---
80/20
---
### 🛡️ 1. **Core of Data Protection & Privacy**
- **Goal**: Protect data **at rest**, **in transit**, and **in use** from unauthorized access, modification, or destruction.
- **Privacy** ensures that personal data is handled according to regulations (e.g., GDPR, HIPAA).

#### Must-Know:
- **Data at rest**: Use encryption (e.g., AES-256).
- **Data in transit**: Use TLS (HTTPS).
- **Data in use**: Use secure enclaves or runtime protections.
- **Regulations**: Understand GDPR, CCPA, etc., and how they influence data practices.

---

### 🔐 2. **Cryptography for Data Protection**
- **Symmetric encryption** (same key for encrypt/decrypt): Fast (e.g., AES).
- **Asymmetric encryption** (public/private keys): Used for secure key exchange and digital signatures (e.g., RSA, ECC).

#### Must-Know:
- **AES**: Standard for encrypting data.
- **RSA/ECC**: Used in digital certificates and key exchange.
- **Hashing**: Ensures data integrity (e.g., SHA-256).

---

### 🔍 3. **Data Discovery & Classification**
- **Purpose**: Identify **where sensitive data resides** and label it appropriately (e.g., PII, PCI, PHI).
- **Why it matters**: You can’t protect what you don’t know you have.

#### Must-Know:
- Tools like **Azure Purview**, **AWS Macie**, or **IBM Guardium** help automate this.
- Classifications trigger policy enforcement (e.g., encryption, masking).

---

### 🧾 4. **Public Key Infrastructure (PKI) Overview**
- **Purpose**: Trust model that manages keys and digital certificates for secure communication.

#### Must-Know:
- **Certificate Authority (CA)**: Issues and verifies digital certificates.
- **Digital Certificate**: Binds a public key to an identity.
- **Trust Chain**: Root CA > Intermediate CA > End Entity Cert.

---

### 🏗️ 5. **PKI Architecture & Deployment**
- **Components**:
  - Root & Intermediate CAs
  - Certificate Revocation Lists (CRL)
  - Online Certificate Status Protocol (OCSP)
- **Deployment Tips**:
  - Use hardware security modules (HSMs).
  - Automate cert renewal (e.g., Let's Encrypt + ACME protocol).

---

### 🔧 6. **OpenSSL**
- **Tool** for managing certs, keys, and crypto ops.

#### Must-Know Commands:
- Generate private key: `openssl genrsa -out key.pem 2048`
- Create CSR: `openssl req -new -key key.pem -out csr.pem`
- View cert: `openssl x509 -in cert.pem -text`

---

### 🔑 7. **Key Lifecycle Management (KLM)**
- **Phases**:
  1. Key generation
  2. Distribution
  3. Rotation
  4. Revocation
  5. Destruction

#### Must-Know:
- Keys should be rotated regularly and securely stored.
- Use **HSMs** or **cloud key vaults** for security.

---

### ☁️ 8. **Azure Key Vault & AWS KMS**
- Both are **cloud-native key management** services.

#### Azure Key Vault:
- Stores secrets, keys, and certs securely.
- Integrates with RBAC & managed identities.

#### AWS KMS:
- Centralized key mgmt with tight integration to AWS services.
- Uses customer-managed or AWS-managed keys.

---

### 🕵️‍♂️ 9. **Data Activity Monitoring (DAM)**
- **Why**: Detect and alert on suspicious access patterns or data exfiltration.
- **Tools**: IBM Guardium, Imperva, native cloud solutions.

#### Must-Know:
- Tracks **who accessed what**, **when**, and **how**.
- Often integrated with SIEM systems for correlation & alerting.

---

### 🧠 10. **IBM Guardium Overview**
- Enterprise DAM solution.
- Can monitor databases (Oracle, SQL Server, DB2, etc.)
- Features: Vulnerability assessment, real-time monitoring, data masking, policy-based alerts.

---

## ⚡ TL;DR Summary:
| Area | What to Remember |
|------|------------------|
| Encryption | AES (symmetric), RSA/ECC (asymmetric), TLS for data in transit |
| PKI | Trust model for certs, CAs issue & manage certs |
| Key Mgmt | Use vaults (Azure Key Vault, AWS KMS), manage lifecycle |
| Data Discovery | Classify & protect sensitive data automatically |
| Monitoring | Use DAM tools (IBM Guardium) to detect data misuse |
| Tools | Learn basic OpenSSL commands for hands-on |

---

