# Manual Security Assessment Report

This document outlines the security measures implemented in the project to ensure a secure web application environment.

## Implemented Security Features
- **Input Validation:** Used `validator.js` to sanitize user inputs and prevent injection attacks.
- **Password Hashing:** Implemented `bcrypt` for secure storage of user passwords.
- **Security Headers:** Integrated `helmet` middleware to secure HTTP headers against common web vulnerabilities (XSS, Clickjacking, etc.).
- **Authentication:** Role-based access control (RBAC) implemented for Admin and User roles.
