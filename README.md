# Attendance & Payroll Management System

A full-stack web application with admin and employee modules featuring facial recognition check-in/out, automated payroll calculation, overtime tracking, and real-time attendance monitoring.


## 📋 Key Features

# 👤Employee Management 
- Employee Account Creation - Register new employees with complete profile information
- Profile Management - Update personal details, contact information, and profile pictures
- Employee ID System - Unique identification for each employee
- Role-Based Access - Separate employee and admin portals
- Account Activation/Deactivation - Control employee access status
  
# ⏰ Attendance Tracking
- Check-In/Check-Out System - Time tracking with photo capture
- Real-Time Attendance Monitoring - Live view of employee attendance status
- Shift Management - Support for different work shifts
- Auto Check-Out - Automatic check-out for employees without approved overtime
- Session Expiry Tracking - Identify missed check-outs
- Attendance History - Complete attendance records with dates and times
- Photo Verification - Capture check-in and check-out photos for security
  
# 💰 Payroll Management
- Automated Payroll Calculation - Bi-monthly payroll processing (5th and 20th of each month)
- Salary Computation - Calculate based on hours worked and hourly rate
- Overtime Pay Integration - Include approved overtime in payroll
- Government Deductions - SSS, PhilHealth, and Pag-IBIG contributions
- Payroll History - View past payroll records
- Custom Payroll Generation - Create and adjust payroll records manually
  
# ⏱️ Overtime Management
- Overtime Request System - Employees can submit overtime requests
- Approval Workflow - Admin approval/rejection of overtime requests
- Overtime Rate Configuration - Custom overtime pay rates per employee
- Overtime Tracking - Monitor approved and pending overtime
- Email Notifications - Notify admins of new overtime requests
  
# 🔐 Authentication & Security
- Secure Login System - Email and password authentication with bcrypt encryption
- Password Reset - OTP-based password recovery via email
- First-Time Login Flow - Mandatory password change for new accounts
- Session Management - Secure user sessions with MongoDB store
- JWT Authentication - Token-based API security
- Protected Routes - Role-based route protection for admin and employee
  
# 📧 Email Notifications
- Account Creation Emails - Welcome emails with login credentials
- Overtime Request Alerts - Notify admins of pending overtime requests
- Password Reset OTP - Send verification codes for password recovery
- Gmail OAuth2 Integration - Secure email sending via Google OAuth
  
# 👨‍💼 Admin Panel
- Admin Account Management - Create and manage admin users
- Employee Management Dashboard - View and manage all employees
- Attendance Monitoring - Track employee attendance in real-time
- Payroll Administration - Generate and manage payroll records
- Overtime Approval - Review and approve/reject overtime requests
- System Configuration - Manage rates, shifts, and system settings
  
# 📊 Reporting & Analytics
- Attendance Reports - Generate attendance summaries by date range
- Payroll Reports - View payroll history and calculations
- Employee Reports - Individual employee attendance and payroll data
- Overtime Reports - Track overtime requests and approvals
  
# 🔧 Technical Features
- RESTful API - Well-structured backend API with Express.js
- MongoDB Database - Scalable NoSQL database for data storage
- File Upload System - Image storage for profile pictures and attendance photos
- Scheduled Jobs - Cron jobs for automated payroll and check-out
- CORS Configuration - Secure cross-origin resource sharing
- Real-Time Updates - Socket.io integration for live updates
- Responsive Design - TailwindCSS for mobile-friendly interface
- Error Handling - Comprehensive error management and validation
  
# 🌐 User Experience
- Intuitive Dashboard - Clean and user-friendly interface
- Profile Customization - Upload and manage profile pictures
- Search & Filter - Easy navigation through records
- Date & Time Management - Timezone support (Asia/Manila)
- Validation & Error Messages - Real-time form validation
- Protected File Access - Secure storage of employee photos and documents


## 🛠 Tech Stack
- MongoDB
- Express
- React
- Next.JS



## ▶️ How to Run Locally
Backend Setup
1. Navigate to backend: cd backend
2. Install dependencies: npm install
3. Configure .env file (see required variables below)
4. Start server: npm start

Frontend Setup
1. Navigate to frontend: cd frontend
2. Install dependencies: npm install
3. Start application: npm start

# Required .env Variables (backend folder)
- MONGO_URI=your_mongodb_connection_string
- EMAIL_USER=your_gmail_address
- EMAIL_APP_PASSWORD=your_gmail_app_password
- CLIENT_ID=your_google_oauth_client_id
- CLIENT_SECRET=your_google_oauth_client_secret
- REFRESH_TOKEN=your_google_oauth_refresh_token
- JWT_SECRET=your_jwt_secret_key
- PORT=5000




## 🧑‍🤝‍🧑 Original Group Project
Originally developed with:  
- Mikko Samaniego  
- Ralph Kenneth De Guzman
- Kenn Marton Mocorro
- Kevin Carl Sunga
- Aaron Joshua Bagain
- Krisma Aliyah Francisco
- Jherome Christopher Lopez
  
### Specific Contribution

# Project Leadership & Client Management
- Led end-to-end project execution from initial client consultation to final delivery and presentation
- Conducted comprehensive requirement gathering sessions to understand client workflows, pain points, and process improvements
- Balanced stakeholder expectations with technical feasibility while considering team constraints and project timeline
  
# System Design & Architecture
- Help designed the overall system architecture and core business logic for the attendance and payroll management system
- Evaluated and validated technical approaches proposed by development team members
- Identified and resolved logical flaws in system design to ensure functional integrity

# Project Management
- Served as Project Manager, utilizing Trello for task distribution and progress tracking
- Maintained regular communication with stakeholders and coordinated team activities
- Monitored development progress while accounting for team's experience level and motivational factors to ensure on-time delivery
  
# Documentation & Quality Assurance
- Created and maintained Software Project Management Plan Document
- Contributed to Software Requirement Specification (SRS) and Software Design Document (SDD)
- Conducted thorough proofreading and quality checks to ensure compliance with project standards and guidelines
- Performed comprehensive manual testing through scenario-based test cases to validate system functionality
