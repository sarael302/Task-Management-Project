# Task Management Application

## Introduction

This Task Management Application is a Java-based web platform developed to optimize project and task management. Designed with Scrum methodology in mind, it provides managers and team members with tools to create, manage, and track backlogs and tasks efficiently. The application features an intuitive interface and robust security measures to streamline collaboration and enhance productivity.

---

## Features

### For Managers
- **Backlog Management**: Create, view, assign, and manage backlogs.
- **Task Assignment**: Assign tasks to team members and monitor their progress.
- **User Management**: Manage team members and their roles.
- **Dashboard**: Get an overview of tasks, deadlines, and project status.

### For Team Members
- **Task Updates**: Update the status of assigned tasks.
- **Profile Management**: View assigned tasks and manage personal information.
- **Backlog Creation**: Create backlogs for personal or team use.

### Application Features
- **Authentication and Authorization**: Secure login and role-based access control.
- **Responsive Design**: User-friendly interface accessible on various devices.
- **Real-Time Updates**: Track project progress dynamically.

---

## Technologies Used

- **Backend**:
  - **Spring Boot**: Framework for backend development.
  - **Spring Security**: Handles authentication and authorization.
  - **H2 Database**: Lightweight relational database for data storage.
  - **Maven**: Dependency and build management tool.

- **Frontend**:
  - **Thymeleaf**: Server-side template engine for dynamic HTML generation.
  - **Bootstrap**: Framework for responsive and modern UI design.
  - **jQuery**: Simplifies DOM manipulation and frontend interactions.

- **Development Tools**:
  - **IntelliJ IDEA**: Integrated Development Environment (IDE) for Java.
  - **StarUML**: Tool for UML modeling and system design.

---

## Architecture

The application follows a **three-tier architecture**:
1. **Presentation Layer** (Frontend): Built with Thymeleaf and Bootstrap for a responsive UI.
2. **Business Logic Layer** (Backend): Managed by Spring Boot for handling logic and HTTP requests.
3. **Data Layer** (Database): Uses H2 for relational data storage.

---

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/task-management-app.git
   cd task-management-app
   ```

2. **Set Up the Environment**:
   - Install Java.
   - Install Maven for dependency management.

3. **Build and Run the Application**:
   ```bash
   mvn clean install
   mvn spring-boot:run
   ```

4. **Access the Application**:
   Open `http://localhost:8080` in your browser.

---

## Key Functionalities

- **Backlog Creation**: Managers can create detailed backlogs with deadlines.
- **Task Assignment**: Backlogs can be assigned to team members dynamically.
- **Status Tracking**: Tasks can be marked as "In Progress" or "Completed."
- **Responsive Notifications**: Visual indicators for approaching deadlines.

---

## Future Enhancements

- Real-time notifications for task updates and deadlines.
- Integration with external tools like Slack or Microsoft Teams.
- Advanced analytics and predictive tools for sprint planning.
- Enhanced customization for the user interface.

---

## To test users
`manager@mail.com`  password: `112233`  
`ann@mail.com`  password: `112233`

---

## inspiration 
https://github.com/sambaf/NHSystem
https://github.com/springframeworkguru/springbootwebapp
https://github.com/gustavoponce7/spring-login
https://github.com/rengreen/task-manager 
  
  
