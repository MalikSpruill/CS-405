# CS-405
Portfolio work for secure coding

# Secure Coding Best Practices

## Overview
This repository focuses on secure coding practices, covering key principles such as the **10 security coding standards**, **defense-in-depth**, and the **Triple-A framework (Authentication, Authorization, and Accounting)**.

## Security Coding Standards
These 10 security coding standards help ensure robust and secure software development:

1. **Input Validation** – Always validate and sanitize user inputs.
2. **Authentication & Authorization** – Implement strong authentication and role-based access control (RBAC).
3. **Secure Session Management** – Use secure cookies, enforce session timeouts, and implement token-based authentication.
4. **Error Handling & Logging** – Avoid exposing sensitive error details and ensure secure logging practices.
5. **Cryptographic Practices** – Use strong encryption algorithms and proper key management.
6. **Data Protection** – Ensure data integrity and confidentiality both at rest and in transit.
7. **Secure Configuration** – Apply secure default settings and avoid hardcoded credentials.
8. **Code Quality & Secure Development Lifecycle (SDLC)** – Follow secure coding guidelines and conduct regular code reviews.
9. **Dependency Management** – Keep third-party libraries and frameworks up to date to prevent supply chain attacks.
10. **Threat Modeling & Security Testing** – Perform regular security assessments, penetration testing, and static/dynamic analysis.

## Defense-in-Depth Strategy
Defense-in-depth ensures multiple layers of security, reducing risks even if one layer is compromised. Key principles include:

- **Network Security** – Firewalls, VPNs, and intrusion detection systems (IDS).
- **Application Security** – Secure coding, input validation, and access control.
- **Data Security** – Encryption, backups, and access restrictions.
- **Endpoint Security** – Antivirus, device control, and patch management.
- **Monitoring & Incident Response** – Continuous monitoring, alerting, and forensic analysis.

## The Triple-A Framework (AAA)
The **Triple-A (AAA) security model** is crucial for secure system design:

1. **Authentication** – Verifying the identity of users and devices.
2. **Authorization** – Granting permissions based on roles and access policies.
3. **Accounting** – Tracking and logging user activities for audit and compliance.

## Secure Coding Resources
- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [CWE (Common Weakness Enumeration)](https://cwe.mitre.org/)
- [NIST Secure Software Development Framework (SSDF)](https://csrc.nist.gov/publications/detail/white-paper/2020/04/23/secure-software-development-framework-ssdf)
- [MITRE ATT&CK Framework](https://attack.mitre.org/)

## Contributing
N/A

## License
N/A
