# Day 2 - Salesforce Platform Basics
## 1. What is Salesforce Platform?
Salesforce is a cloud-based CRM (Customer Relationship Management) platform that helps businesses manage customers, sales, services, and business processes. It allows organizations to store data, automate workflows, and build applications on a secure cloud environment.
Salesforce provides tools for:
- Customer management
- Sales tracking
- Automation
- App development
- Reporting and analytics
It uses a multi-tenant cloud architecture where multiple organizations use the same platform securely.
# 2. Explain App, Object, and Tab
## App
An App in Salesforce is a collection of related tools, objects, tabs, and features designed for a specific business purpose.
### Example:
- Sales App
- Service App
- College Management App
Apps help users work in a specific environment based on their role.
## Object
Objects are database tables used to store data in Salesforce.
### Standard Objects:
- Account
- Contact
- Opportunity
### Custom Objects:
- Student
- Complaint
- Attendance
Objects contain records and fields similar to rows and columns in a database.
## Tab
Tabs are user interface components used to access objects, records, dashboards, or applications.
### Example:
- Accounts Tab
- Contacts Tab
- Reports Tab
Tabs help users navigate through Salesforce easily.
# 3. Difference Between Configuration and Coding
| Configuration | Coding |
| No programming required | Requires programming knowledge |
| Uses clicks and settings | Uses Apex and Lightning components |
| Faster and easier | More flexible and powerful |
| Suitable for simple automation | Suitable for complex business logic |
## Configuration Examples
1. Creating validation rules
2. Designing page layouts
## Coding Examples
1. Creating custom business logic using Apex
2. Integrating Salesforce with external systems
# 4. My System Design
## App Name
College Management App
## Objects
- Student
- Faculty
- Courses
- Attendance
- Complaints
## User Interaction
### Admin
- Manage student and faculty records
- Monitor complaints
### Faculty
- Update attendance
- Manage course information
### Students
- View course details
- Submit complaints