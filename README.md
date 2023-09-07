# Sticky Note Management System

Welcome to the Sticky Note Management System, a full-stack MERN (MongoDB, Express.js, React.js, Node.js) project designed to replace the current sticky note system in your organization. This application allows you to efficiently manage and track notes, assign them to specific employees, and control user roles and permissions.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Roles and Permissions](#roles-and-permissions)
- [Screenshots](#screenshots)

## Project Overview

The Sticky Note Management System is designed to streamline your note-taking process, enhance communication within your organization, and provide secure access control for different user roles. The main objectives of this project are:

1. **Replace Current Sticky Note System:** Transition from traditional sticky notes to a digital, more organized solution.

2. **Public-Facing Page:** Display basic contact information to the public.

3. **Employee Login:** Secure login system for employees to access the notes app.

4. **Welcome Page:** A welcoming interface after successful login.

5. **Easy Navigation:** User-friendly navigation throughout the application.

6. **User Information:** Display the current user's information and assigned role.

7. **Logout Option:** Allow users to log out when they are done.

8. **User Authentication:** Require users to login at least once per week for security.

9. **Employee Access Management:** Provide the ability to revoke employee access quickly if needed.

10. **Note Management:**

    - Notes are assigned to specific employees.
    - Notes have a ticket number, title, note body, created date, and updated date.
    - Notes can be in either OPEN or COMPLETED status.
    - Users can be Employees, Managers, or Admins.

11. **Permissions:**

    - Notes can only be deleted by Managers or Admins.
    - Anyone can create a note when a customer checks in.
    - Employees can only view and edit their assigned notes.
    - Managers and Admins can view, edit, and delete all notes.

12. **User Settings:**

    - Only Managers and Admins can access User Settings.
    - Only Managers and Admins can create new users.

13. **Responsive Design:**

    - The application is primarily designed for desktop use but is also accessible on mobile devices." > README.md

14. **Replace Current Sticky Note System:** Transition from traditional sticky notes to a digital, more organized solution.

15. **Public-Facing Page:** Display basic contact information to the public.

## Installation

To run this project locally, follow these steps:

1. Clone this repository to your local machine:

```
git clone https://github.com/tanvircs/MERN-techNotes-APP.git

```

2. Install server dependencies:

```
npm install

```

3. Start the server and client concurrently:

```
npm run dev

```

## Usage

1. Register an Admin user to get started.
2. Log in with your Admin credentials.
3. Create new users with different roles (Admin, Manager, Employee).
4. Create, edit, and manage notes according to your role.
5. Explore the user settings section for additional controls.

## Roles and Permissions

- **Admins**
- Create and manage users.
- **Managers**
- **Employees**
