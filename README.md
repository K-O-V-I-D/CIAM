# CIAM
Container Identity Access Management Protocol
Container Identity Access Management (CIAM) is an application designed to manage the identity and access of containers within a virtualized environment. This protocol aims to provide a secure and efficient way to control and monitor container access, ensuring that only authorized users can interact with specific containers. Docker, a popular containerization platform, is leveraged as the hypervisor, enabling virtualization within containers. This protocol is implemented using Docker as the hypervisor, Python for the backend, Next.js for the frontend, and JSON for blockchain storage. CIAM is designed as an API-based system that acts as a bridge between the frontend and backend components.

## Overview:

The Container Identity Access Management (CIAM) protocol employs a Docker-based system for robust identity and access control in a secure environment.

## Features:

Role-Based Access: Users classified as guests, root, or regular users with varying privileges.
Blockchain Integration: JSON-stored blockchain ensures tamper-resistant data management.
API Connectivity: RESTful APIs connect the frontend (Next.js) and backend (Python), enabling dynamic container and API management.
Secure Password Handling: Passwords hashed using SHA-256 for robust security.
Automated Container Creation: Bash scripts automate container generation, enhancing efficiency.

## Working:

User Registration: Register users through a secure process.
Docker Verification: Authenticate Docker instances using hashed passwords.
API Assignment: Dynamically assign APIs based on user roles.
Blockchain Logging: Store data in a blockchain for traceability and security.

## Tools & Technologies:

Next.js: Frontend development.
Python: Backend scripting.
Docker: Containerization and virtualization.
Bash: Scripting for automation.
JSON: Blockchain data storage.
This comprehensive solution ensures efficient, secure, and role-specific container identity and access management in Docker environments.
