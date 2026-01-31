# APAS: Automated Performance Appraisal System
APAS is a full-stack web application designed to streamline the corporate performance review process. It enables seamless goal setting, real-time progress tracking, 360-degree feedback, and automated performance scoring using a weighted-average algorithm.

 # Key Features
 # For Employees
Goal Management: Create, edit, and track individual goals aligned with company objectives.

Self-Appraisal: Submit self-ratings and comments for review.

Progress Dashboard: Real-time visibility into the appraisal workflow status.

 # For Managers
Team Overview: Monitor the appraisal progress of all direct reports in one view.

Approval Workflow: Approve or reject employee goals with feedback.

Performance Review: Rate employee performance and provide professional growth comments.

 # For HR Administrators
Cycle Management: Create and manage appraisal cycles and set high-level company goals.

Advanced Analytics: View department-wide performance reports and identify underperformers (below-average scores).

Audit Logging: Complete transparency of all database changes (Goal edits, rating updates, etc.).

# Getting Started
Prerequisites 

Node.js (v20+)

MySQL Server (v8.0+)

# 1. Database Setup
Create a new MySQL database named apas_db.

Run the .sql files

# 2. Backend Installation
   cd backend
   
   npm install# Create a .env file with:
   
   DB_HOST, DB_USER, DB_PASS, DB_NAME, PORT
   
   npm start

# 3. Frontend Installation

  cd frontend
  
  npm install
  
  npm run dev
   
