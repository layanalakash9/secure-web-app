# STRIDE Threat Modeling Report
## Application Name: Secure Web Application

| Threat Type | Description | Example in Your App | Mitigation |
| :--- | :--- | :--- | :--- |
| **S**poofing | Impersonating a user | Unauthorized login | Use JWT with secure signature |
| **T**ampering | Modifying data | Changing DB records | Input validation & HTTPS |
| **R**epudiation | Denying actions | No audit logs | Enable logging for user actions |
| **I**nformation Disclosure | Leaking data | Error messages showing info | Use generic error messages |
| **D**enial of Service | Making app unavailable | Too many login requests | Implement rate limiting |
| **E**levation of Privilege | Unauthorized access | User accessing admin panel | Role-based access control (RBAC) |
