# Enterprise Microsoft Entra ID Administration Lab

## Project Objective

Develop hands-on experience administering Microsoft Entra ID by building an enterprise identity environment from the ground up. This lab focuses on understanding not only *how* Microsoft Entra features work, but *why* organizations implement them to manage identities, applications, devices, and security at scale.

---

## Version Roadmap

### v0.1 – Project Initialization

* Create GitHub repository
* Create README
* Create CHANGELOG
* Create screenshots folder
* Establish project structure

---

### v0.2 – Identity Management

**Concept:** Every employee has an identity.

* Create users
* Configure user properties
* Organize employee identities

**Learn**

* User lifecycle
* Identity objects
* Employee identity management

---

### v0.3 – Group-Based Access Management

**Concept:** Manage permissions through groups instead of individual users.

* Create Security Groups
* Assign users to groups
* Create All Employees group

**Learn**

* Security Groups
* Access management
* Least privilege
* Scalable permission management

---

### v0.4 – Administrative Access (RBAC)

**Concept:** Separate administrative responsibilities from business access.

* Explore built-in administrative roles
* Assign administrative roles
* Understand RBAC

**Learn**

* Administrative Roles
* Least privilege
* Delegated administration
* Tenant administration

---

### v0.5 – Collaboration & Microsoft 365 Groups

**Concept:** Separate collaboration from permission management.

* Create Microsoft 365 Groups
* Configure Owners
* Add Members

**Learn**

* Collaboration workspaces
* Microsoft 365 Groups
* Group Owners vs Members
* Difference between Security Groups and Microsoft 365 Groups

---

### v0.6 – Enterprise Applications & Identity Integration

**Concept:** Applications trust Microsoft Entra to authenticate users.

* Explore Enterprise Applications
* Understand Service Principals
* Review Application ID and Object ID
* Understand Single Sign-On

**Learn**

* Identity Provider (IdP)
* Enterprise Applications
* Service Principals
* Centralized authentication
* Application assignments

---

## v0.7 – Application Identity, Authentication & Authorization

**Concept:** Applications have identities just like users and must authenticate before they can securely access Microsoft services.

### Tasks

* Create an App Registration
* Explore the Client ID and Object ID
* Generate a Client Secret
* Explore Microsoft Graph API permissions
* Compare Delegated vs Application permissions
* Locate the associated Service Principal (Enterprise Application)
* Understand the OAuth authentication flow

### Learn

* Application Identity
* App Registrations
* Service Principals
* OAuth 2.0
* Client Credentials Flow
* Access Tokens
* Microsoft Graph Authentication
* Delegated vs Application Permissions
* Least Privilege for Applications

---

### v0.8 – Microsoft Graph API Fundamentals

**Concept:** Microsoft Graph is the unified API that applications use to interact with Microsoft Entra and other Microsoft 365 services.

**Tasks**

* Explore Microsoft Graph Explorer
* Authenticate using Microsoft Entra
* Explore REST endpoints
* Retrieve users
* Retrieve groups
* Analyze JSON responses
* Understand Microsoft Graph resources

**Learn**

* Microsoft Graph API
* REST APIs
* Endpoints
* Resources
* JSON Responses
* OAuth Access Tokens in Practice

---

### v0.9 – Enterprise Identity Architecture

**Concept:** Bring together users, groups, applications, authentication, and authorization into a complete enterprise identity workflow.

**Tasks**

* Review the authentication flow
* Review the authorization flow
* Diagram the employee onboarding process
* Diagram the employee offboarding process
* Review least privilege implementation
* Review App Registrations and Service Principals
* Review Microsoft Graph integration

**Learn**

* Identity Lifecycle
* Enterprise Identity Architecture
* Authentication vs Authorization
* Identity Automation
* Least Privilege
* Identity Governance
