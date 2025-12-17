# CS-305
This repository contains my selected artifact from CS-305: Software Security: the completed Practices for Secure Software Report from Project Two. It demonstrates my 
refactoring of a Spring Boot application for Artemis Financial, where I implemented SHA-256 cryptographic hashing for verifiable data integrity with unique timestamps, 
enforced HTTPS using a self signed certificate supporting modern ciphers like AES-256-GCM, and validated all changes through OWASP dependency check scans that 
confirmed no new vulnerabilities were introduced.

Artemis Financial is a financial consulting firm that develops personalized plans for savings, retirement, investments, and insurance. The company needed to modernize 
their web application by adding secure checksum verification and encrypted communications to protect sensitive client data. I excelled in vulnerability identification 
through manual review and static analysis, which underscores the importance of secure coding for preventing breaches, ensuring compliance with PCI-DSS and GDPR, 
preserving client trust, and reducing long-term risks. Configuring HTTPS provided valuable hands-on challenges. In future projects, I would leverage tools like 
dependency check, SonarQube, NIST NVD, and threat modeling for risk assessment. I verified functionality and security through thorough testing and post refactoring scans. 
Useful practices included Java Keytool, strong cryptography, minimal attack surface design, and early security integration. To future employers, I would highlight this 
report as practical evidence of applying OWASP and NIST aligned secure coding in a real world scenario, directly relevant to development, security, or compliance roles.
