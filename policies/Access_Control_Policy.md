# 🔒 Access Control Policy | E-Commerce Startup

*Document Version 1.0*

## 1. Purpose
This policy establishes minimum requirements for managing and controlling access to all organizational systems, applications, and customer data to minimize the risk of unauthorized access, protect data confidentiality, and comply with security best practices.

## 2. Scope
This policy applies to all employees, contractors, and third-party vendors who are granted access to the company's IT resources, including the e-commerce platform, cloud environment, and internal networks.

## 3. Policy Requirements

### 3.1. Authentication and Identity
* **Multi-Factor Authentication (MFA):** All privileged accounts (e.g., admin, cloud console, database) and accounts accessing customer PII **must** utilize MFA.
* **Password Management:** Passwords must meet minimum complexity requirements (length, mixture of characters) and be managed via a centralized vault/manager.
* **Account Termination:** Access must be **revoked immediately** upon employee or contractor termination (or status change).

### 3.2. Authorization (Least Privilege)
* **Principle of Least Privilege (PoLP):** Users shall only be granted the minimum access necessary to perform their job functions. All access requests must be reviewed and approved.
* **Role-Based Access Control (RBAC):** Access permissions shall be granted based on established job roles (e.g., Marketing, Customer Service, Developer) rather than individual names.
* **Segregation of Duties (SoD):** Where feasible, duties that, if combined, could result in fraud or significant error must be separated.

## 4. Control Mapping (NIST Alignment)

This policy is aligned with the **NIST Cybersecurity Framework (CSF) Protect Function** and the following **NIST SP 800-53** Access Control (AC) family controls:

| Policy Requirement | NIST SP 800-53 Control | GRC Concept Demonstrated |
| :--- | :--- | :--- |
| **MFA Required** | AC-2 | Account Management (Strong Auth) |
| **Least Privilege** | AC-6 | Access Enforcement |
| **RBAC** | AC-3 | Access Enforcement (Role-Based) |
| **Account Termination** | AC-2 (5) | Account Management (Access Revocation) |
