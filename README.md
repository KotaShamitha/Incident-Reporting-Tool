# Incident Reporting Tool

## Project Overview
The Incident Reporting Tool is a web application built with Angular and Firebase. It streamlines the reporting and resolution of incidents within an organization by ensuring efficient, role-based workflows. The tool features a clean user interface, role-based dashboards, and real-time data synchronization.

---

## Features

### 1. **Authentication & Authorization**
- Users can log in using their mobile number and OTP.
- Role-based dashboards for Admins and Reporters.
- Route protection via Angular Auth Guards.

### 2. **Admin Features**
- Dashboard displaying all incidents categorized by status (Open, In Progress, Resolved).
- Assign incidents to Reporters.
- Mark incidents as resolved.
- View a list of Reporters and their assigned incidents.

### 3. **Reporter Features**
- Dashboard displaying incidents reported by them.
- Update the status of incidents (e.g., "In Progress").
- Add comments to incidents.

### 4. **User Interface**
- Clean and responsive design.
- Visual indicators for incident priority (Low, Medium, High).

### 5. **Problem Solving**
- Real-time incident reporting and tracking.
- Edge case handling to prevent duplicate incident reports and unauthorized edits.

### 6. **Role-Based CRUD Operations**
- **Admins**: Create, view, assign, and resolve incidents.
- **Reporters**: Report incidents, update statuses, and add comments.

### 7. **Deployment**
- Hosted using Firebase Hosting.

---

## Technologies Used
- **Front End**: Angular 19 (standalone components).
- **Back End**: Firebase (Authentication, Firestore, Hosting).
- **UI Library**: Angular Material.
- **Version Control**: Git and GitHub.

---

## Project Setup
### Prerequisites
- Node.js (v18 or higher)
- Angular CLI
- Firebase CLI

### Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Configure Firebase:
   - Create a Firebase project.
   - Enable Authentication (Phone Authentication).
   - Set up Firestore Database.
   - Add Firebase project configuration in `src/environments/environment.ts`.
4. Serve the application:
   ```bash
   ng serve
   ```

---

## Usage
### Admin Login
- Mobile: `+919876543210`
- OTP: Any valid OTP for demo purposes.

### Reporter Logins
- **Bob Reporter**
  - Mobile: `+919123456789`
  - OTP: Any valid OTP for demo purposes.
- **Charlie Reporter**
  - Mobile: `+919234567890`
  - OTP: Any valid OTP for demo purposes.

### Incidents
- **Incident 1**: Water Leakage in Office
  - Priority: High
  - Reported By: Bob Reporter
  - Status: Open
- **Incident 2**: Broken Monitor
  - Priority: Medium
  - Reported By: Charlie Reporter
  - Status: In Progress

---

## Deployment
1. Build the project:
   ```bash
   ng build
   ```
2. Deploy using Firebase:
   ```bash
   firebase deploy
   ```
3. Access the application via the Firebase Hosting URL.

---

## Evaluation Criteria
| Criteria                  | Marks |
|---------------------------|-------|
| Project Setup             | 10    |
| Authentication & Authorization | 15 |
| UI Design                 | 15    |
| Problem Solving           | 15    |
| Role-Based CRUD           | 10    |
| Angular & TypeScript Concepts | 10 |
| Coding Standards          | 10    |
| Code Quality              | 5     |
| Deployment & Submission   | 10    |
| **Total**                 | 100   |
| **Pass Marks**            | 70    |

---

## Deliverables
- GitHub repository link: `<https://github.com/KotaShamitha/Incident-Reporting-Tool>`

---

## Rules
- The use of generative AI tools is strictly prohibited.
- Submit the project as a GitHub repository link with the Firebase Hosting URL.
- Ensure the project is functional and bug-free.

---

