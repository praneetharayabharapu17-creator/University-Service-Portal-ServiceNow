# 🎓 University Service Portal - ServiceNow

A comprehensive **University Service Portal** built using **ServiceNow App Engine Studio** to simplify university administration by automating leave management, student grievance handling, and course registration.

---

## 📌 Project Overview

The University Service Portal is designed to digitize and automate common academic and administrative processes within a university. The application provides role-based access, workflow automation, email notifications, reporting, and dashboards to improve efficiency and user experience.

---

## ✨ Features

### 📝 Leave Management
- Apply for leave
- Faculty approval/rejection
- Automatic email notifications
- Leave history tracking

### 📚 Course Management
- Create and manage university courses
- Maintain course details
- Course catalog management

### 🎓 Course Registration
- Student course registration
- Registration status tracking
- Automated confirmation email

### 📢 Student Grievance Management
- Submit grievances
- Automatic faculty assignment
- Faculty resolution
- Resolution notification to students

### 🔐 Security
- Role-Based Access Control (RBAC)
- Custom ACLs
- Student, Faculty and University Admin roles

### 📊 Reporting & Analytics
- Leave Requests by Status
- Leave Requests by Leave Type
- Student Grievances by Status
- Course Registrations by Status
- University Administration Dashboard

---

# 🏗️ Modules

- Leave Request
- Student Grievance
- Course
- Course Registration

---

# ⚙️ Technologies Used

- ServiceNow App Engine Studio
- Flow Designer
- Notifications
- Roles
- Access Control Lists (ACLs)
- Reports
- Dashboards
- Custom Tables
- Forms

---

# 👥 User Roles

## Student

- Apply Leave
- Register Courses
- Submit Grievances
- View Own Records

---

## Faculty

- Review Leave Requests
- Resolve Student Grievances
- View Assigned Records

---

## University Admin

- Full System Access
- Manage Courses
- Manage Users
- View Reports
- Access Dashboard

---

# 🔄 Workflows

## Leave Request Workflow

```
Leave Request Created
        ↓
Faculty Approval
        ↓
Approved / Rejected
        ↓
Email Notification
```

---

## Student Grievance Workflow

```
Student Submits Grievance
        ↓
Status = Open
        ↓
Assign Faculty
        ↓
Faculty Receives Email
        ↓
Faculty Resolves Grievance
        ↓
Student Receives Resolution Email
```

---

## Course Registration Workflow

```
Student Registers
        ↓
Registration Created
        ↓
Status Updated
        ↓
Confirmation Email Sent
```

---

# 🔒 Security Implementation

### Roles

- Student
- Faculty
- University Admin

### ACLs

Access Control Lists were implemented for:

- Leave Request
- Student Grievance
- Course
- Course Registration

Operations secured:

- Create
- Read
- Write
- Delete

---

# 📈 Reports

The application includes the following reports:

- Leave Requests by Status
- Leave Requests by Leave Type
- Student Grievances by Status
- Course Registrations by Status

---

# 📊 Dashboard

**University Administration Dashboard**

Includes:

- Leave Requests by Status
- Leave Requests by Leave Type
- Student Grievances by Status
- Course Registrations by Status

---

# 📷 Screenshots

Screenshots are available inside the **Screenshots** folder.

Example screenshots include:

- Dashboard
- Leave Request Form
- Student Grievance Form
- Course Registration Form
- Leave Workflow
- Student Grievance Workflow
- Course Registration Workflow
- Reports
- Roles
- ACLs

---

# 📂 Repository Structure

```
University-Service-Portal-ServiceNow
│
├── README.md
├── LICENSE
│
├── Application
│   └── University_Service_Portal_Update_Set.xml
│
├── Documentation
│   └── Installation_Guide.md
│
└── Screenshots
```

---

# 🚀 Installation

Refer to:

```
Documentation/Installation_Guide.md
```

for detailed installation instructions.

---

# 🔮 Future Enhancements

- Student Portal Dashboard
- Faculty Dashboard
- Course Capacity Management
- Approval Workflows for Course Registration
- Attendance Management
- Examination Module
- AI Chatbot Integration
- Mobile Responsive Portal

---

# 👨‍💻 Author

**Sriram Rayabharapu**

Third-Year Engineering Student

---

# ⭐ If you found this project useful, consider giving it a star!
