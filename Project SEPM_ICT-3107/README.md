# Smart Student Task & Assignment Tracking System

A Java desktop application designed to help students organize courses,
manage tasks and assignments, monitor deadlines, and track academic
progress.

> **Project type:** Software Engineering Project Management (SEPM)\
> **Application:** Java desktop application\
> **UI:** Java Swing with FlatLaf\
> **Database:** SQLite\
> **Build tool:** Maven\
> **Development environment:** IntelliJ IDEA, JDK 26

------------------------------------------------------------------------

## Table of Contents

-   [Overview](#overview)
-   [Problem Statement](#problem-statement)
-   [Objectives](#objectives)
-   [Target Users](#target-users)
-   [Scope and Features](#scope-and-features)
-   [Technology Stack](#technology-stack)
-   [System Workflow](#system-workflow)
-   [Software Process Model](#software-process-model)
-   [Project Schedule](#project-schedule)
-   [Milestones and Deliverables](#milestones-and-deliverables)
-   [System Diagrams](#system-diagrams)
-   [Proposed Class Structure](#proposed-class-structure)
-   [Project Structure](#project-structure)
-   [Setup and Run](#setup-and-run)
-   [Testing Plan](#testing-plan)
-   [Risks and Mitigation](#risks-and-mitigation)
-   [Expected Outcome](#expected-outcome)
-   [Future Improvements](#future-improvements)
-   [Project Status](#project-status)

------------------------------------------------------------------------

## Overview

**Smart Student Task & Assignment Tracking System** is intended to
provide students with one place to organize their academic work. It
brings course information, tasks, assignments, deadlines, and progress
tracking into a single desktop interface.

The project is being developed as a SEPM assignment. Its documentation
will cover requirements, a software process model, project planning,
system diagrams, a Java prototype, testing, and a GitHub repository.

## Problem Statement

Students may need to track academic activities across different courses,
notebooks, calendars, and online platforms. When deadlines and tasks are
spread across multiple places, it can be difficult to prioritize work
and monitor progress.

This project aims to provide a centralized system for managing courses,
tasks, assignments, and their deadlines.

## Objectives

-   Organize courses in one application.
-   Create and manage academic tasks and assignments.
-   Record deadlines and completion status.
-   Provide a dashboard for a quick overview of academic work.
-   Store application data locally using SQLite.
-   Demonstrate object-oriented design through Java classes.
-   Align the implementation with the project's UML and database design.
-   Document the development plan and results for the SEPM assignment.

## Target Users

-   University and college students.
-   Students who want a centralized way to manage academic activities.

## Scope and Features

### Planned core features

-   **Dashboard:** Overview of courses, tasks, assignments, and
    progress.
-   **Course management:** Add and view course information.
-   **Task management:** Record tasks, priorities, deadlines, and
    status.
-   **Assignment management:** Organize assignment details and due
    dates.
-   **Progress tracking:** Review completion status.
-   **Local persistence:** Save data in an SQLite database.

The final feature set should reflect what is actually implemented in the
submitted version. Do not describe a planned feature as completed until
it has been developed and tested.

## Technology Stack

  -----------------------------------------------------------------------
  Technology                          Purpose
  ----------------------------------- -----------------------------------
  Java (JDK 26 environment)           Application logic and
                                      object-oriented implementation

  Java Swing                          Desktop graphical user interface

  FlatLaf                             Modern Swing look and feel

  SQLite                              Local data storage

  SQLite JDBC                         Java-to-SQLite connectivity

  Maven                               Dependency and build management

  IntelliJ IDEA                       Development environment

  LaTeX                               Professional project
                                      proposal/documentation
  -----------------------------------------------------------------------

## System Workflow

1.  The application starts from `App.java`.
2.  The Swing interface is initialized on the Event Dispatch Thread.
3.  FlatLaf configures the application's appearance.
4.  The database initialization code prepares the SQLite database.
5.  `MainFrame` opens the main application window.
6.  The user accesses the available course, task, assignment, and
    progress features.
7.  Data is stored in SQLite where the relevant feature has been
    implemented.

``` text
App.java
   |
   v
Initialize Swing UI and FlatLaf
   |
   v
Initialize SQLite database
   |
   v
Open MainFrame
   |
   +---- Dashboard
   +---- Courses
   +---- Tasks
   +---- Assignments
   |
   v
Save and retrieve application data
```

## Software Process Model

The project plans to use **Agile Scrum**, developing the application in
manageable increments. Each iteration can include planning, design,
implementation, testing, review, and feedback.

``` text
Requirements
     |
     v
Sprint Planning
     |
     v
Design -> Development -> Testing
     ^                    |
     |                    v
     +---- Review <--- Feedback
```

Agile Scrum is suitable for this student project because features and
diagrams can be refined incrementally as implementation and testing
reveal issues.

## Project Schedule

The following is a proposed 10-week plan. Adjust the weeks to match the
actual course calendar and work completed.

  ------------------------------------------------------------------------
                          Week Main activity         Expected deliverable
  ---------------------------- --------------------- ---------------------
                             1 Requirement analysis  Requirements list

                             2 Proposal preparation  Initial project
                                                     proposal

                             3 Process model and     Schedule and
                               planning              milestone plan

                             4 DFD and Use Case      DFD and Use Case
                               design                Diagram

                             5 Activity Diagram and  Activity Diagram and
                               ERD                   ERD

                             6 Class and Object      UML class/object
                               Diagrams              designs

                             7 Java GUI development  Initial working
                                                     interface

                             8 SQLite integration    Integrated prototype
                               and core features     

                             9 Testing and           Test cases and test
                               corrections           results

                            10 Final documentation   Final proposal,
                               and packaging         diagrams, and GitHub
                                                     repository
  ------------------------------------------------------------------------

## Milestones and Deliverables

  -----------------------------------------------------------------------
  Milestone                           Deliverable / evidence
  ----------------------------------- -----------------------------------
  Requirements agreed                 Requirements documented

  Proposal drafted                    Proposal source and PDF

  System design completed             Required system/UML diagrams

  Prototype implemented               Java source code and runnable
                                      application

  Data storage integrated             SQLite database and related code

  Testing completed                   Test cases, results, and
                                      corrections

  Submission prepared                 README, proposal, diagrams, source
                                      code, and GitHub link
  -----------------------------------------------------------------------

## Gantt Chart

A Gantt chart should be included in the proposal or in the `Gantt/`
folder. The table below provides a simple schedule outline; convert it
to a visual chart for the final submission.

  Activity                      W1   W2   W3   W4   W5   W6   W7   W8   W9   W10
  ---------------------------- ---- ---- ---- ---- ---- ---- ---- ---- ---- -----
  Requirements                  ■                                           
  Proposal                           ■    ■                                 
  Process model and schedule              ■                                 
  DFD and Use Case                             ■                            
  Activity Diagram and ERD                          ■                       
  Class and Object Diagrams                              ■                  
  Java GUI                                                    ■             
  SQLite and features                                              ■        
  Testing                                                               ■   
  Final documentation                                                         ■

## System Diagrams

The assignment requires the following six diagrams. Keep the names and
relationships consistent across the proposal, database, class diagram,
and Java implementation.

1.  **Data Flow Diagram (DFD):** Shows how information moves between the
    student, application processes, and data store.
2.  **Use Case Diagram:** Shows the user and the actions supported by
    the system.
3.  **Activity Diagram:** Shows the workflow for a selected activity,
    such as creating and saving a task.
4.  **Entity Relationship Diagram (ERD):** Shows database entities,
    attributes, keys, and relationships.
5.  **Class Diagram:** Shows the planned Java classes, attributes,
    methods, and relationships.
6.  **Object Diagram:** Shows example instances of classes and their
    attribute values at a particular moment.

Store the exported diagrams in `UML/`. Include editable source files if
available, as well as image exports for easy viewing.

## Proposed Class Structure

The following are candidate domain classes to consider for the class
diagram and implementation:

-   `User`
-   `Student`
-   `Teacher` (include only if teacher functionality is within scope)
-   `Course`
-   `Task`
-   `Assignment`
-   `Progress`
-   `Database`
-   `MainFrame`
-   `App`

The assignment requires **at least five classes represented in the Class
Diagram and used in the prototype**. Choose the final classes based on
the features that will actually be implemented. The UML diagram and Java
code should match; do not count a class as implemented just because it
appears in a diagram.

## Project Structure

A suggested repository layout is:

``` text
Smart-Student-Task-Tracking-System/
├── README.md
├── Proposal/
│   ├── Project-Proposal.tex
│   └── Project-Proposal.pdf
├── UML/
│   ├── DFD.png
│   ├── Use-Case.png
│   ├── Activity-Diagram.png
│   ├── ERD.png
│   ├── Class-Diagram.png
│   └── Object-Diagram.png
├── Gantt/
│   └── Gantt-Chart.png
├── src/
│   └── main/
│       └── java/
│           └── com/
│               └── mashrafi/
│                   └── smartstudent/
│                       ├── App.java
│                       ├── data/
│                       ├── model/
│                       └── ui/
├── database/
├── screenshots/
├── pom.xml
└── .gitignore
```

This is a suggested structure. Keep the actual repository structure and
filenames accurate to the files you commit. If the SQLite database is
generated locally at runtime, decide whether a database file should be
committed; avoid committing private or unnecessary local data.

## Setup and Run

### Prerequisites

-   JDK compatible with the project configuration (the development
    environment described for this project uses JDK 26).
-   Maven.
-   IntelliJ IDEA or another Java IDE.

### Run in IntelliJ IDEA

1.  Clone or download the repository.
2.  Open the project folder containing `pom.xml`.
3.  Allow Maven to load the project dependencies.
4.  Confirm that the configured JDK is selected.
5.  Run `App.java`.

### Run with Maven

From the project root, use:

``` bash
mvn clean compile
```

If the `pom.xml` includes a configured execution plugin, use the
corresponding Maven run command. Otherwise, run
`com.mashrafi.smartstudent.App` from IntelliJ IDEA or configure the
appropriate Maven plugin first.

## Testing Plan

Test the implemented features and record actual results in the final
report.

  -----------------------------------------------------------------------
  Test area                           Example test
  ----------------------------------- -----------------------------------
  Application startup                 Application opens without an
                                      unhandled exception

  Database initialization             Required tables are created or
                                      available

  Course management                   Valid course data can be saved and
                                      retrieved

  Task management                     A task can be added and its status
                                      updated

  Assignment management               Assignment details and due dates
                                      are handled correctly

  Input validation                    Invalid or missing values produce a
                                      useful message

  Persistence                         Saved data remains available after
                                      restarting the application

  GUI usability                       Main navigation and controls work
                                      as intended
  -----------------------------------------------------------------------

Only mark a test as **Pass** after running it and recording the observed
result.

## Risks and Mitigation

  -----------------------------------------------------------------------
  Risk                                Mitigation
  ----------------------------------- -----------------------------------
  UML and code become inconsistent    Update the diagrams whenever the
                                      class structure changes

  Scope grows too large               Prioritize the required core
                                      features

  Database integration problems       Test database operations separately
                                      before GUI integration

  Insufficient time for testing       Reserve a dedicated testing period

  Missing submission artifacts        Use the deliverables checklist
                                      before submitting

  Environment differences             Document the required JDK and Maven
                                      setup
  -----------------------------------------------------------------------

## Expected Outcome

The expected outcome is a documented Java desktop prototype that helps
students organize academic activities and demonstrates software
engineering planning, UML modelling, object-oriented implementation,
database integration, and testing.

## Future Improvements

Possible extensions, subject to time and requirements:

-   Notifications for upcoming deadlines.
-   Search, filtering, and sorting.
-   Calendar view.
-   Data export and backup.
-   Enhanced progress summaries.
-   Optional cloud synchronization.

## Project Status

**Status:** In development / academic prototype.

Update this status as features are completed and tested. Add screenshots
of the actual running application to `screenshots/` and include the
final GitHub repository URL in the project proposal or submission form.

------------------------------------------------------------------------

## Submission Checklist

-   [ ] Project proposal source (`.tex`) and compiled PDF
-   [ ] DFD
-   [ ] Use Case Diagram
-   [ ] Activity Diagram
-   [ ] ERD
-   [ ] Class Diagram
-   [ ] Object Diagram
-   [ ] Gantt chart
-   [ ] Java prototype with at least five diagram-aligned classes
-   [ ] SQLite integration, if included in the implemented scope
-   [ ] Test cases and actual results
-   [ ] Screenshots of the running application
-   [ ] Updated README and GitHub repository link
