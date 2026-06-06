# Secure Web Application

## Description
A secure web application developed for the Secure Software Development course. It implements core security principles including authentication, input validation, and threat modeling.

## Tech Stack
- Backend: Node.js, Express
- Database: MongoDB
- Security: bcrypt, helmet, validator.js

## Features
- User Registration/Login with role-based access (Admin/User).
- Password hashing using bcrypt.
- Input validation and sanitization.
- STRIDE & DREAD security modeling documentation.
- Automated code scanning using GitHub CodeQL.

## Threat Modeling
- STRIDE report: See `docs/STRIDE_Threat_Model.md`
- DREAD report: See `docs/DREAD_Risk_Assessment.md`

## Deployment
Instructions:
1. `git clone <your-repo-url>`
2. `npm install`
3. `npm start`
