# RecruitEase - System Diagrams

This document contains all the use case diagrams and flow diagrams for the RecruitEase Campus Recruitment Portal.

---

## Use Case Diagrams

### 1. Admin Module Use Case Diagram

![Admin Module Use Case Diagram](https://nyc3.digitaloceanspaces.com/bhindi-drive/files/66819f6e-f43d-49d0-a4f6-dbd57a6d58ed/2026-02-19T18-10-51-011Z-2c3ee313-nano-banana-pro_1771524650854.jpg)

**Admin Capabilities:**
- Secure Login & Profile Management
- Manage HR Users (Add, Edit, Delete, View)
- Manage Job Postings (View All, Approve, Delete)
- Manage Company/Client Details (Add, Edit, Delete, View)
- View Reports (Daily Job Postings, HR Activity, Application Statistics)
- View Student Feedback
- Authentication Validation & Email Notifications

---

### 2. HR Module Use Case Diagram

![HR Module Use Case Diagram](https://nyc3.digitaloceanspaces.com/bhindi-drive/files/66819f6e-f43d-49d0-a4f6-dbd57a6d58ed/2026-02-19T18-11-14-419Z-52bff802-nano-banana-pro_1771524674283.jpg)

**HR Capabilities:**
- Secure Login & Profile Management
- Add Company/Client Details (Name, Email, Address, Contact, Logo)
- Create/Edit/Delete Job Postings
- View Job Applicants
- Update Application Status (Applied, Shortlisted, Rejected)
- View Dashboard (Total Jobs, Applicants, Hiring Statistics)
- Download Applicant Resumes
- Real-time Chat with Students
- Security Features (Disable Copy-Paste & Screenshot for sensitive data)

---

### 3. Student Module Use Case Diagram

![Student Module Use Case Diagram](https://nyc3.digitaloceanspaces.com/bhindi-drive/files/66819f6e-f43d-49d0-a4f6-dbd57a6d58ed/2026-02-19T18-11-36-142Z-fe3d9239-nano-banana-pro_1771524695056.jpg)

**Student Capabilities:**
- Secure Login & Profile Management
- View Job Openings (based on registered domain)
- Filter Jobs (by Location, Department, Company)
- Apply for Jobs
- Upload/Update Resume (with validation)
- View Application History & Status
- Real-time Chat with HR
- Email Notifications for applications and status updates
- Optional: Advanced Search & Save Jobs for Later

---

## Flow Diagrams

### 1. Admin Module - Workflow

![Admin Module Simple Flowchart](https://nyc3.digitaloceanspaces.com/bhindi-drive/files/66819f6e-f43d-49d0-a4f6-dbd57a6d58ed/2026-02-19T18-19-03-024Z-25d15f8d-nano-banana-pro_1771525142896.jpg)

**Simple Flow:** 
```
Login → Dashboard → Manage HR/Jobs/Companies/Reports/Feedback → Update Database → Logout
```

**Key Actions:**
- Manage HR Users
- Manage Job Postings
- Manage Companies
- View Reports
- View Feedback

---

### 2. HR Module - Workflow

![HR Module Simple Flowchart](https://nyc3.digitaloceanspaces.com/bhindi-drive/files/66819f6e-f43d-49d0-a4f6-dbd57a6d58ed/2026-02-19T18-19-21-203Z-f188331f-nano-banana-pro_1771525161099.jpg)

**Simple Flow:** 
```
Login → Dashboard → Manage Companies/Jobs/Applicants/Status/Chat → Send Notifications → Update Database → Logout
```

**Key Actions:**
- Manage Companies
- Create/Edit Job Postings
- View Applicants
- Update Application Status
- Chat with Students

---

### 3. Student Module - Workflow

![Student Module Simple Flowchart](https://nyc3.digitaloceanspaces.com/bhindi-drive/files/66819f6e-f43d-49d0-a4f6-dbd57a6d58ed/2026-02-19T18-19-41-850Z-2bc19c97-nano-banana-pro_1771525181747.jpg)

**Simple Flow:** 
```
Login → Dashboard → Browse/Apply/Resume/Status/Chat → Update Database → Receive Notifications → Logout
```

**Key Actions:**
- Browse & Filter Jobs
- Apply for Jobs
- Upload/Update Resume
- View Application Status
- Chat with HR

---

## Summary

This document provides a comprehensive visual overview of the RecruitEase system architecture:

- **Use Case Diagrams**: Show the interactions between actors (Admin, HR, Student) and the system functionalities
- **Flow Diagrams**: Illustrate the high-level workflow for each user role from login to logout

These diagrams help understand the system requirements, user interactions, and overall application flow.
