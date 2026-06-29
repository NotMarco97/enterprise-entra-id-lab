# Changelog

All notable changes to this project will be documented in this file.

---

## v0.1 - Project Initialization

### Added
- Created GitHub repository.
- Established project folder structure.
- Added initial documentation.
- Created `README.md`.
- Created `CHANGELOG.md`.
- Created `docs/`, `screenshots/`, and `diagrams/` directories.

---

## v0.2 - Identity Foundation

### Added
- Created enterprise user accounts for the IT Solutions lab.
- Established a standardized user naming convention.
- Added Version 2 documentation.
- Added screenshots demonstrating user creation and properties.

### Design Decisions
- User identities were created without permissions or group memberships.
- Access management will be implemented through Security Groups in the next version to separate identity from authorization.

---

## v0.3 Security Groups

### Added
- created approriate security groups.
- Assigned users to appropriate groups.
- Added Version 0.3 documentation and screenshots.


## v0.4 - Role-Based Access Control (RBAC)

### Added
- Assigned built-in Microsoft Entra administrative roles to designated users.
- Implemented role assignments following the principle of least privilege.
- Added screenshot demonstrating RBAC configuration.

## v0.5 Microsoft 365 Groups

### Added
- Implemented Microsoft 365 Groups (Collaboration).
- Added a user in the Microsoft 365 group as owner.

## v0.6 Understanding Enterpise Applications

### Added
- Observed and analyzed how Enterprise Applications worked
- Understood the difference between Application ID and Object ID

## v0.7 Application Identity, Authentication & Authorization

### Added
- Created an App Registration for the Identity Administration Lab.
- Generated a Client Secret for application authentication.
- Explored Microsoft Graph API permissions.
- Compared Delegated and Application permissions.
- Verified the associated Service Principal (Enterprise Application).
- Studied the OAuth 2.0 Client Credentials Flow.
- Learned how Access Tokens are used to authenticate Microsoft Graph requests.

## v0.8 Microsoft Graph API Fundamentals

### Added 
- Explored Microsoft Graph Explorer.
- Reviewed Graph API endpoints such as `/me` and `/users`.
- Observed how Microsoft Graph requires permissions before returning tenant data.
- Compared delegated access for '/me' with broader directory access for '/users'.
