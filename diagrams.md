# RecruitEase - System Diagrams

This document contains the use case diagram and flow diagrams for the RecruitEase Campus Recruitment Portal.

---

## Use Case Diagram

### RecruitEase System - Complete Use Case Diagram

![RecruitEase Complete Use Case Diagram](https://nyc3.digitaloceanspaces.com/bhindi-drive/files/66819f6e-f43d-49d0-a4f6-dbd57a6d58ed/2026-02-19T18-04-17-192Z-6b1b337a-nano-banana-pro_1771524257014.jpg)

**System Actors:**
- **Admin**: System administrator with full control
- **HR**: Human resources personnel managing recruitment
- **Student**: Job seekers applying for positions

**Admin Use Cases:**
- Login & Authentication
- Manage HR Users
- Manage Job Postings
- Manage Company/Client Details
- View Reports
- View Student Feedback

**HR Use Cases:**
- Login & Authentication
- Add/Manage Company Details
- Create/Edit/Delete Job Postings
- View Applicants
- Update Application Status
- View Dashboard (jobs, applicants, statistics)
- Download Resumes

**Student Use Cases:**
- Login & Authentication
- View Job Openings
- Filter Jobs (Location, Department, Company)
- Apply for Jobs
- Upload/Update Resume
- View Application History & Status

**Shared Features:**
- Email Notifications (all actors)
- Real-time Chat (HR ↔ Student)

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

- **Use Case Diagram**: Shows the interactions between all actors (Admin, HR, Student) and the system functionalities in one unified view
- **Flow Diagrams**: Illustrate the high-level workflow for each user role from login to logout

These diagrams help understand the system requirements, user interactions, and overall application flow.
