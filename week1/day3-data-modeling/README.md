# Day 3 - Data Modeling in Salesforce

## 1. Difference Between App

An App in Salesforce is a collection of related tabs, objects, and tools used for a particular business process. It helps users work in one organized area. Example: Sales App.

## Difference Between Object

An Object is like a database table that stores data in Salesforce. It contains records and fields. Example: Student Object, Account Object.

## Difference Between Record

A Record is a single entry stored inside an object. It is similar to one row in a database table. Example: One student’s details.

## Difference Between Field

A Field stores a specific piece of information inside a record. It is similar to a column in a database table. Example: Student Name, Email, Phone Number.

---

# 2. Standard vs Custom Objects

## Standard Objects

Standard objects are already provided by Salesforce for common business operations. These are prebuilt objects used in CRM systems.

Examples:
- Account
- Contact
- Opportunity
- Lead

## Custom Objects

Custom objects are created by users based on company requirements. These objects help organizations store their own business data.

Examples:
- Student
- Faculty
- Course
- Department

---

# 3. College Management System Data Model

## Objects Used

- Student
- Faculty
- Course
- Department

## Relationships

One department can contain many students.

One department can contain many faculty members.

One department can contain many courses.

One student can enroll in multiple courses.

One course can contain multiple students.

## Relationship Type

Lookup relationships can be used between:
- Student and Department
- Faculty and Department
- Course and Department

Many-to-many relationship can exist between Student and Course.

## Simple Diagram

Department
   |
   |---- Student
   |
   |---- Faculty
   |
   |---- Course