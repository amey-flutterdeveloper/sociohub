SocioHub — NoBrokerHood Clone

A Flutter-based learning and portfolio project inspired by NoBrokerHood, built to understand and implement real-world society management workflows using Flutter and modern application architecture.

Disclaimer: This project is an independent learning/portfolio clone. It is not affiliated with, sponsored by, or endorsed by NoBrokerHood or NoBroker Technologies.

📱 About the Project

SocioHub is a society management mobile application designed around common apartment-community workflows for residents, security personnel, and administrators.

The project focuses on recreating real-world application flows such as visitor management, maintenance tracking, complaints, amenities booking, announcements, notifications, and role-based access.

🎯 Project Objective

The main objective of this project is to gain hands-on experience building a production-style Flutter application by studying an existing real-world product and implementing its core workflows independently.

✨ Core Features
Authentication
User registration and login
Secure authentication
Role-based access
Resident Management
Resident profile
Family/member information
Society information
Visitor Management
Add visitor
Visitor approval/rejection
Visitor history
Visitor status tracking
Maintenance
View maintenance charges
Payment status
Maintenance history
Complaints & Service Requests
Create complaint
Track complaint status
Update/resolve requests
Complaint history
Amenities
View available amenities
Check availability
Book amenities
View booking history
Society Communication
Society announcements
Notices
Resident communication
Notifications
Additional Features
Search and filtering
Local data persistence
Loading, error and empty states
Responsive Flutter UI
🛠️ Tech Stack

Frontend

Flutter
Dart
Riverpod

Backend

Laravel
REST API
PHP

Database

MySQL

Networking

Dio

Local Storage

Hive / SharedPreferences

Development Tools

Git
GitHub
Postman
Android Studio / VS Code
🏗️ Architecture

The application follows a feature-based architecture with separation between presentation, domain and data layers.

lib/
├── app/
├── core/
├── features/
│   ├── authentication/
│   ├── residents/
│   ├── visitors/
│   ├── maintenance/
│   ├── complaints/
│   ├── amenities/
│   ├── announcements/
│   └── notifications/
└── shared/
🔄 Example Workflow
Visitor Approval
Visitor arrives
      ↓
Security creates visitor request
      ↓
Resident receives notification
      ↓
Resident approves / rejects
      ↓
Visitor status is updated
      ↓
Entry is recorded

📸 Screenshots
Screenshots will be added as the application modules are completed.
