# Smart Student Task & Assignment Tracking System

## Initial Project Proposal

### Student Information

    | Information | Details |
    |---|---|
    | **Student Name** | Md. Mashrafi Rahman |
    | **Student ID** | IT-24034 |
    | **Course** | SEPM-ICT-3107 |
    | **Project Type** | Individual Software Engineering Project |
    | **Development Model** | Agile Scrum |
    | **Programming Language** | Java 26 |
    | **GUI Technology** | Java Swing with FlatLaf |
    | **Database** | SQLite |
    | **Development Environment** | IntelliJ IDEA |
    | **Build Tool** | Maven |
    
    ---

# 1. Introduction

University students are required to manage multiple courses, assignments, projects, laboratory work, presentations, examinations, and other academic activities. Managing these activities manually or using multiple unrelated applications can make it difficult to keep track of deadlines, priorities, and overall academic progress.

The **Smart Student Task & Assignment Tracking System** is proposed as a Java-based desktop application that provides students with a centralized platform for managing their academic activities.

The system will allow students to manage courses, create and organize tasks and assignments, set deadlines and priorities, update completion status, and monitor their academic progress through a simple and user-friendly graphical interface.

The project will demonstrate the practical application of software engineering concepts including requirements analysis, software process models, UML modelling, object-oriented programming, database design, GUI development, testing, and project documentation.

---

# 2. Background

Students commonly use notebooks, messaging applications, calendar applications, spreadsheets, or separate productivity tools to manage academic activities. Although these tools can be useful individually, students may need to switch between multiple platforms to manage different types of academic information.

For example, a student may record an assignment deadline in one application, course information in another location, and personal tasks in a notebook. This can result in missed deadlines, poor prioritization, and difficulty understanding overall academic progress.

The proposed system addresses this problem by providing a centralized academic task management environment.

---

# 3. Problem Statement

Students may face several difficulties when managing academic responsibilities:

- Multiple assignments and tasks may have different deadlines.
- Important academic tasks may be forgotten.
- Students may have difficulty identifying high-priority work.
- Academic information may be distributed across different applications.
- There may be no centralized overview of pending and completed activities.
- Students may have difficulty measuring their overall academic task completion progress.

Therefore, a simple and centralized academic task and assignment tracking system is required.

---

# 4. Proposed Solution

The proposed **Smart Student Task & Assignment Tracking System** will provide a centralized Java desktop application where students can manage their academic activities.

The system will provide functionality for:

- Managing courses.
- Creating and managing tasks.
- Creating and managing assignments.
- Setting deadlines.
- Setting task priorities.
- Updating task status.
- Tracking completed and pending activities.
- Searching and filtering academic activities.
- Monitoring overall progress.

The application will use **SQLite** for persistent local data storage and **Java Swing with FlatLaf** for the graphical user interface.

---

# 5. Aim of the Project

The main aim of this project is to develop a simple, reliable, and user-friendly desktop application that helps university students organize their academic tasks and assignments while monitoring their progress.

---

# 6. Project Objectives

The major objectives of the project are:

1. To develop a centralized academic task management system.
2. To allow students to manage their courses.
3. To allow students to create, edit, delete, and complete academic tasks.
4. To manage academic assignments and deadlines.
5. To provide task priority management.
6. To display pending and completed academic activities.
7. To provide progress tracking.
8. To provide search and filtering functionality.
9. To store academic information persistently using SQLite.
10. To develop a modern and user-friendly Java desktop GUI.
11. To demonstrate object-oriented programming concepts.
12. To apply software engineering methodologies throughout the development process.
13. To design the system using appropriate UML diagrams.
14. To test the system systematically before final submission.

---

# 7. Project Scope

## 7.1 In-Scope Features

The initial version of the system will include:

- Student login.
- Dashboard.
- Course management.
- Task management.
- Assignment management.
- Deadline management.
- Priority management.
- Task status management.
- Progress tracking.
- Search functionality.
- Filtering functionality.
- SQLite database storage.
- Java desktop graphical interface.

## 7.2 Out-of-Scope Features

The initial version will not include:

- Online examinations.
- Video conferencing.
- Online payment systems.
- University-wide administration.
- Cloud synchronization.
- Mobile application.
- Real-time communication.

These features may be considered as future enhancements.

---

# 8. Target Users

The primary target users of the system are:

### University Students

Students will use the application to manage:

- Courses.
- Assignments.
- Tasks.
- Deadlines.
- Priorities.
- Completion status.
- Academic progress.

Future versions may introduce separate roles for teachers and administrators.

---

# 9. Major System Features

## 9.1 Student Login

The system will provide a login interface through which the student can access the application.

## 9.2 Dashboard

The dashboard will provide a summary of academic activities, such as:

- Total courses.
- Pending tasks.
- Completed tasks.
- Upcoming assignments.
- Upcoming deadlines.
- Overall progress.

## 9.3 Course Management

The student will be able to:

- Add courses.
- View courses.
- Edit course information.
- Delete courses.

Course information may include:

- Course code.
- Course title.
- Instructor.
- Semester.

## 9.4 Task Management

Students will be able to create academic tasks containing information such as:

- Task title.
- Description.
- Course.
- Priority.
- Deadline.
- Status.

The student will also be able to edit, delete, and mark tasks as completed.

## 9.5 Assignment Management

The assignment module will allow students to manage:

- Assignment title.
- Course.
- Description.
- Submission deadline.
- Completion/submission status.

## 9.6 Deadline Tracking

The system will display upcoming deadlines so that students can identify tasks that require attention.

## 9.7 Priority Management

Tasks may be categorized according to priority, for example:

- High.
- Medium.
- Low.

## 9.8 Progress Tracking

The system will calculate and display the student's task completion progress.

For example:

**Total Tasks = 20**

**Completed Tasks = 15**

**Progress = 75%**

## 9.9 Search and Filtering

Students will be able to search and filter tasks and assignments according to criteria such as:

- Course.
- Status.
- Priority.
- Deadline.

---

# 10. Functional Requirements

| ID | Requirement | Description |
|---|---|---|
| FR-01 | Login | Student can access the application through login. |
| FR-02 | Dashboard | System displays an overview of academic activities. |
| FR-03 | Course Management | Student can add, edit, delete, and view courses. |
| FR-04 | Task Management | Student can create, edit, delete, and complete tasks. |
| FR-05 | Assignment Management | Student can manage academic assignments. |
| FR-06 | Deadline Tracking | System stores and displays deadlines. |
| FR-07 | Priority Management | Student can assign priorities to tasks. |
| FR-08 | Status Management | Student can update task completion status. |
| FR-09 | Progress Tracking | System calculates and displays progress. |
| FR-10 | Search | Student can search academic activities. |
| FR-11 | Filtering | Student can filter tasks and assignments. |
| FR-12 | Data Persistence | System stores information in SQLite. |

---

# 11. Non-Functional Requirements

## 11.1 Usability

The interface should be simple, clear, and easy for students to understand.

## 11.2 Performance

Common operations such as adding, updating, searching, and viewing tasks should respond quickly.

## 11.3 Reliability

The system should store data reliably and maintain information after the application is closed and reopened.

## 11.4 Maintainability

The application should use modular object-oriented design so that future developers can modify or extend the system.

## 11.5 Portability

The application should run on systems that support the required Java environment.

## 11.6 Security

The application should protect user information and validate user input.

## 11.7 Scalability

The design should allow future features such as cloud synchronization, mobile support, and additional user roles.

---

# 12. Technology Stack

| Technology | Purpose |
|---|---|
| **Java 26** | Main programming language |
| **Java Swing** | Desktop GUI |
| **FlatLaf** | Modern Swing interface |
| **SQLite** | Local database |
| **Maven** | Dependency and project management |
| **IntelliJ IDEA** | Development environment |
| **Git** | Version control |
| **GitHub** | Source code and project submission |
| **LaTeX / Overleaf** | Professional project documentation |

---

# 13. Object-Oriented Design

The project will apply object-oriented programming principles.

The main proposed classes are:

- `User`
- `Student`
- `Teacher`
- `Course`
- `Task`
- `Assignment`
- `Progress`

Additional application classes will be used for GUI and database operations.

The Class Diagram and Java implementation will be designed consistently so that the classes shown in the UML model are represented in the actual Java application.

---

# 14. Software Process Model

The project will follow the **Agile Scrum software development model**.

Agile Scrum has been selected because the system can be developed incrementally through multiple stages or sprints.

The general development cycle will be:

**Product Backlog → Sprint Planning → Development → Testing → Review → Feedback → Next Sprint**

This approach allows problems to be identified early and enables improvements to be incorporated throughout development.

---

# 15. Proposed Development Sprints

## Sprint 1 — Requirements and Planning

Activities:

- Identify project problem.
- Define objectives.
- Define scope.
- Identify requirements.
- Prepare initial proposal.

Deliverables:

- Requirements document.
- Initial project proposal.

## Sprint 2 — System Design

Activities:

- Design DFD.
- Design Use Case Diagram.
- Design Activity Diagram.
- Design ERD.
- Design Class Diagram.
- Design Object Diagram.

Deliverables:

- Complete UML/system design.

## Sprint 3 — Database and GUI Design

Activities:

- Design SQLite database.
- Create Java project structure.
- Design main GUI.
- Create dashboard prototype.

Deliverables:

- Database schema.
- GUI prototype.

## Sprint 4 — Core Development

Activities:

- Implement Java classes.
- Implement course management.
- Implement task management.
- Implement assignment management.

Deliverables:

- Working core application.

## Sprint 5 — Integration and Testing

Activities:

- Integrate SQLite.
- Implement progress tracking.
- Implement search/filter.
- Perform functional testing.
- Fix identified problems.

Deliverables:

- Functional application.
- Test results.

## Sprint 6 — Documentation and Submission

Activities:

- Prepare final proposal.
- Prepare README.
- Prepare screenshots.
- Prepare final PDF.
- Organize GitHub repository.

Deliverables:

- Final documentation.
- GitHub repository.
- Final project submission.

---

# 16. Project Schedule

| Week | Main Activity | Milestone | Deliverable |
|---|---|---|---|
| Week 1 | Requirement Analysis | M1 | Requirements |
| Week 2 | Proposal Development | M2 | Initial Proposal |
| Week 3 | UML Design | M3 | DFD, Use Case, Activity |
| Week 4 | Database & UML Completion | M4 | ERD, Class, Object Diagram |
| Week 5 | GUI Development | M5 | GUI Prototype |
| Week 6 | Java Development | M6 | Core Application |
| Week 7 | SQLite Integration | M7 | Database-enabled Application |
| Week 8 | Feature Completion | M8 | Functional Prototype |
| Week 9 | Testing & Debugging | M9 | Test Report |
| Week 10 | Documentation & Submission | M10 | Final Project |

---

# 17. Project Milestones

The project will have the following major milestones:

- **M1:** Requirements completed.
- **M2:** Project proposal completed.
- **M3:** Initial UML diagrams completed.
- **M4:** Complete system and database design.
- **M5:** GUI prototype completed.
- **M6:** Core Java implementation completed.
- **M7:** SQLite integration completed.
- **M8:** Functional prototype completed.
- **M9:** Testing completed.
- **M10:** Final documentation and GitHub submission completed.

---

# 18. Project Deliverables

The following deliverables will be produced:

1. Initial project proposal.
2. Requirements specification.
3. Agile development plan.
4. Project schedule.
5. Gantt chart.
6. Data Flow Diagram.
7. Use Case Diagram.
8. Activity Diagram.
9. Entity Relationship Diagram.
10. Class Diagram.
11. Object Diagram.
12. Java source code.
13. Java GUI.
14. SQLite database.
15. Testing documentation.
16. Project README.
17. LaTeX source.
18. Final PDF proposal.
19. GitHub repository.

---

# 19. UML and System Design

The following diagrams will be developed:

### 19.1 Data Flow Diagram

The DFD will represent the flow of information between the student, application processes, and database.

### 19.2 Use Case Diagram

The Use Case Diagram will represent the interaction between the student and system functionalities.

### 19.3 Activity Diagram

The Activity Diagram will represent workflows such as creating and completing a task.

### 19.4 Entity Relationship Diagram

The ERD will represent database entities and relationships.

Core entities will include:

- Student
- Course
- Task
- Assignment
- Progress

### 19.5 Class Diagram

The Class Diagram will represent the main object-oriented structure of the application.

Proposed classes include:

- User
- Student
- Teacher
- Course
- Task
- Assignment
- Progress

### 19.6 Object Diagram

The Object Diagram will show example runtime objects created from the classes.

---

# 20. Graphical User Interface

The application will use a modern Java desktop interface.

The main interface will contain:

- Sidebar navigation.
- Dashboard.
- Course section.
- Task section.
- Assignment section.
- Progress section.
- Logout option.

The interface will be implemented using Java Swing and FlatLaf.

The project will implement at least five classes from the Class Diagram in the actual Java application.

---

# 21. Database Design

SQLite will be used as the local persistent database.

The proposed database will contain tables such as:

- `students`
- `teachers`
- `courses`
- `tasks`
- `assignments`
- `progress`

The Java application will communicate with SQLite through a dedicated database layer.

This separation will help keep database operations independent from GUI components.

---

# 22. Risk Analysis

| Risk | Impact | Mitigation |
|---|---|---|
| Development delay | High | Follow sprint schedule and milestones |
| GUI complexity | Medium | Develop interface incrementally |
| Database errors | High | Test database operations independently |
| Integration problems | Medium | Integrate modules step-by-step |
| Requirement changes | Medium | Maintain an Agile backlog |
| Data loss | High | Use database backup and validation |
| Testing time shortage | Medium | Start testing during development |

---

# 23. Testing Strategy

Testing will be performed throughout development.

Important test cases will include:

- Application startup.
- Student login.
- Add course.
- Edit course.
- Delete course.
- Add task.
- Edit task.
- Delete task.
- Complete task.
- Add assignment.
- Update assignment.
- Deadline display.
- Search.
- Filtering.
- Progress calculation.
- SQLite data persistence.

Both normal and invalid inputs will be tested.

---

# 24. Expected Outcome

At the end of the project, a functional Java desktop application is expected to be produced.

The completed application will allow a student to:

- Manage academic courses.
- Manage academic tasks.
- Manage assignments.
- Track deadlines.
- Set priorities.
- Monitor completion status.
- Search and filter activities.
- Monitor academic progress.
- Store information persistently using SQLite.

The project will also demonstrate the practical application of software engineering and project management concepts.

---

# 25. Future Enhancements

Future versions of the system may include:

- Cloud synchronization.
- Android/mobile application.
- Web application.
- Teacher dashboard.
- Administrator dashboard.
- Email notifications.
- Automatic deadline reminders.
- Calendar integration.
- AI-based task prioritization.
- Academic performance analytics.
- Multi-device synchronization.
- Online collaboration.

---

# 26. Conclusion

The **Smart Student Task & Assignment Tracking System** is proposed as an individual software engineering project to address the practical problem of managing academic tasks and assignments.

The system will provide students with a centralized platform for managing courses, tasks, assignments, deadlines, priorities, and academic progress.

The project will follow the Agile Scrum development model and will apply software engineering practices throughout the project lifecycle. Requirements analysis, project planning, UML modelling, database design, Java object-oriented programming, GUI development, testing, and documentation will all be incorporated into the development process.

The project will be implemented using Java 26, Java Swing with FlatLaf, SQLite, Maven, and IntelliJ IDEA.

The final outcome will be a functional desktop application supported by professional project documentation, UML diagrams, a project schedule, Gantt chart, testing documentation, and a GitHub repository.

---

# 27. Final Submission Structure

The final GitHub repository will contain:

```text
Smart-Student-Task-Tracking-System/
│
├── README.md
│
├── Proposal/
│   ├── Project-Proposal.tex
│   └── Project-Proposal.pdf
│
├── UML/
│   ├── DFD.png
│   ├── Use-Case-Diagram.png
│   ├── Activity-Diagram.png
│   ├── ERD.png
│   ├── Class-Diagram.png
│   └── Object-Diagram.png
│
├── Gantt/
│   └── Gantt-Chart.png
│
├── src/
│   └── main/
│       └── java/
│
├── database/
│
├── screenshots/
│
├── test/
│
└── pom.xml
```

---

# 28. Student Declaration

I, **Md. Mashrafi Rahman (IT-24034)**, propose to develop the **Smart Student Task & Assignment Tracking System** as an individual software engineering project for the course **SEPM-ICT-3107**.

The project will be developed using the Agile Scrum methodology and will follow appropriate software engineering practices from requirements analysis through implementation, testing, documentation, and final submission.
