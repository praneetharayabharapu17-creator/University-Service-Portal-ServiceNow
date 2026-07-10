# University Service Portal - Installation Guide

## Overview

This guide explains how to import and configure the University Service Portal application in a ServiceNow Personal Developer Instance (PDI).

---

## Prerequisites

- ServiceNow Personal Developer Instance (Australia Release or later)
- System Administrator (admin) role
- Flow Designer plugin enabled
- App Engine Studio enabled

---

## Installation Steps

### Step 1 Import the Update Set

1. Log in to your ServiceNow instance.
2. Navigate to

```
System Update Sets → Retrieved Update Sets
```

3. Click Import Update Set from XML.
4. Select

```
University_Service_Portal_Update_Set.xml
```

5. Upload the file.

---

### Step 2 Commit the Update Set

1. Open the imported update set.
2. Click Preview Update Set.
3. Resolve any preview issues if prompted.
4. Click Commit Update Set.

---

### Step 3 Verify the Application

Navigate to

```
University Service Portal
```

Verify that the following modules are available

- Leave Request
- Student Grievance
- Course
- Course Registration

---

### Step 4 Verify Workflows

Open Flow Designer and ensure the following flows are active

- Leave Request Workflow
- Student Grievance Workflow
- Course Registration Workflow

If any flow is inactive, click Activate.

---

### Step 5 Verify Roles

Confirm the following custom roles exist

- Student
- Faculty
- University Admin

Assign the roles to the required users or groups.

---

### Step 6 Verify ACLs

Navigate to

```
System Security → Access Control (ACL)
```

Verify that ACLs are available for

- Leave Request
- Student Grievance
- Course
- Course Registration

---

### Step 7 Verify Reports

Open the Reports module and verify the following reports exist

- Leave Requests by Status
- Student Grievances by Status
- Course Registrations by Status
- Leave Requests by Leave Type

---

### Step 8 Verify Dashboard

Open the dashboard

```
University Administration Dashboard
```

Ensure all report widgets load correctly.

---

## Testing

Create sample records to verify the application.

### Leave Request

- Submit a leave request.
- Approve or reject it.
- Verify workflow execution.

### Student Grievance

- Submit a grievance.
- Assign it to faculty.
- Resolve the grievance.
- Verify workflow execution.

### Course Registration

- Register for a course.
- Verify registration status update.

---

## Technologies Used

- ServiceNow App Engine Studio
- Flow Designer
- Notifications
- Reports
- Dashboards
- Access Control Lists (ACLs)
- Roles
- Forms
- Custom Tables

---

## Notes

Some Personal Developer Instances have outbound email disabled by default. In such cases, email notifications will be created in System Mailboxes but may not be delivered externally.

---

## Author

Sriram Rayabharapu

University Service Portal - ServiceNow Project