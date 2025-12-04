1. Title

Software Requirements Specification (SRS)
Project: Apna Tailor
Prepared By: Muhammad Ranjha (S22BINFT1M01065)
Submitted To: Ms. Sara Fareed
Department: Information Technology
Faculty of Computing, The Islamia University of Bahawalpur

2. Summary
   
2.1 Background

Apna Tailor is a mobile application developed using Flutter and Hive local database.

It helps tailoring shops efficiently manage customer information.

The app works completely offline, eliminating the need for internet connectivity.

Male and female records are maintained separately for better data organization.

2.2 Key Functionalities

Splash screen on app startup for smooth experience.

Separate record management for male and female clients.

Complete CRUD operations, including add, update, delete, view, and search.

2.3 Findings

Hive ensures fast local data storage with excellent offline performance.

The interface is simple and easy for tailoring shop staff to use.

Gender-based separation makes customer data well organized.

2.4 Requirements

App must run smoothly on all Android devices.

All data stored locally using Hive (no server required).

App must be fast and lightweight.

UI should be easy to use for non-technical users.

3. Introduction

Apna Tailor is an offline-first mobile application created to help tailoring shops store and manage customer measurements and details. Built using Flutter and Hive, the app allows tailors to handle customer records efficiently without needing an internet connection. Both male and female records are managed independently for clear and organized data access.

4. Purpose

The purpose of the Apna Tailor app is to digitize customer record management for tailoring shops. Instead of manual notebooks, the app offers a fast, organized, and offline digital record system. It aims to improve accuracy, productivity, and ease of access for tailoring businesses.

5. Scope

The scope of the app includes:

Managing male and female customer records separately

Storing data offline using Hive

Supporting CRUD operations

Helping tailoring shops access and update customer measurements quickly

Providing a lightweight, fast app for daily use on Android phones

The app does not include cloud sync or online features.

6. Product Perspective

Apna Tailor is a standalone mobile system designed exclusively for tailoring shops.
It uses:

Flutter for cross-platform development

Hive for fast, offline, local data storage

No backend server or internet connection is required.

7. User Characteristics

Primary users:

Tailoring shop owners

Tailoring staff

User traits:

Mostly non-technical

Prefer simple and direct UI

Need quick access to customer details

Often work in offline areas

The app is built to be user-friendly and easy to navigate.

8. Literature Review

Most existing management apps require an internet connection and are not designed specifically for tailoring shops. Many tailoring apps do not provide offline support or gender-based data separation.

Apna Tailor fills these gaps with:

Offline-first experience

Hive local database

Male/female category segregation

9. Proposed Technologies

Flutter: For building a smooth and responsive Android application

Hive Database: For fast, secure, offline storage

Dart Language: For app development logic

10. Functional Requirements

Add new customer records (male/female)

Update existing customer information

Delete customer records

View customer details

Search records by name/keyword

Show splash screen on app launch

Store all data offline using Hive

11. Non-Functional Requirements

Performance: App must remain fast, even with large data.

Usability: Simple UI for non-technical users.

Reliability: Data must remain safe even without internet.

Security: Customer data should not be accessible to unauthorized users.

Compatibility: Must run smoothly on entry-level Android devices.

Lightweight: Low storage and RAM usage.

12. Use Cases & Flow
12.1 User Launches App

Splash screen appears

User selects Male or Female category

12.2 Add Customer Record

User enters customer info & measurements

Data saved in Hive database

12.3 View Customer Records

User views list of all customers

Selects a customer to view details

12.4 Update Customer Record

User edits customer info

Updated data saved in database

12.5 Delete Customer Record

User deletes unwanted records

Data removed permanently

12.6 Search Customer Record

User enters keyword

App shows filtered results

13. References

Flutter Documentation

Hive Database Documentation
