# MERN-techNotes-APP

Welcome to the Sticky Note Management System, a full-stack MERN (MongoDB, Express.js, React.js, Node.js) project designed to replace the current sticky note system in your organization. This application allows you to efficiently manage and track notes, assign them to specific employees, and control user roles and permissions.

Table of Contents
Project Overview
Features
Installation
Usage
Roles and Permissions
Screenshots
Contributing
License
Project Overview
The Sticky Note Management System is designed to streamline your note-taking process, enhance communication within your organization, and provide secure access control for different user roles. The main objectives of this project are:

Replace Current Sticky Note System: Transition from traditional sticky notes to a digital, more organized solution.

Public-Facing Page: Display basic contact information to the public.

Employee Login: Secure login system for employees to access the notes app.

Welcome Page: A welcoming interface after successful login.

Easy Navigation: User-friendly navigation throughout the application.

User Information: Display the current user's information and assigned role.

Logout Option: Allow users to log out when they are done.

User Authentication: Require users to login at least once per week for security.

Employee Access Management: Provide the ability to revoke employee access quickly if needed.

Note Management:

Notes are assigned to specific employees.
Notes have a ticket number, title, note body, created date, and updated date.
Notes can be in either OPEN or COMPLETED status.
Users can be Employees, Managers, or Admins.
Permissions:

Notes can only be deleted by Managers or Admins.
Anyone can create a note when a customer checks in.
Employees can only view and edit their assigned notes.
Managers and Admins can view, edit, and delete all notes.
User Settings:

Only Managers and Admins can access User Settings.
Only Managers and Admins can create new users.
Responsive Design:

The application is primarily designed for desktop use but is also accessible on mobile devices.
