
# CampusFix – Campus Technical Issue and Resource Management Portal

CampusFix is a Software Engineering project focused on simplifying the reporting, tracking, and resolution of technical and infrastructural issues within a college campus. It provides a structured approach to managing campus maintenance requests and improving coordination between users, administrators, and technicians.

## Project Objectives

- Centralize campus issue reporting.
- Enable issue tracking and status monitoring.
- Improve coordination between administrators and technicians.
- Prioritize issues based on severity and urgency.
- Maintain issue history and resolution records.
- Improve accountability and transparency in campus maintenance.

## Project Documentation

This repository contains the Software Requirements Specification (SRS) and UML diagrams for CampusFix.

| Document | Description |
|---|---|
| [SRS IEEE](SRS_IEEE.docx) | Software requirements, system scope, functional and non-functional requirements, and project specifications. |
| [Activity Diagram](activity%20diagram.pdf) | Represents the workflow of reporting and resolving campus issues. |
| [Class Diagram](class%20diagram.pdf) | Represents system classes and their relationships. |
| [Sequence Diagram](sequence%20diagram.pdf) | Illustrates interactions between users and system components over time. |
| [State Diagram](state%20diagram.pdf) | Shows issue states and transitions throughout the issue lifecycle. |
| [Use Case Diagram](usecase%20diagram.pdf) | Represents system actors and their interactions with CampusFix. |

## Main Features

- **Issue Reporting:** Submit campus issues with descriptions, categories, locations, priorities, and optional image evidence.
- **Issue Tracking:** Monitor the current status of reported issues.
- **Technician Assignment:** Allow administrators to assign verified issues to technicians.
- **Status Management:** Track issues from submission to resolution and closure.
- **Notifications:** Notify relevant users about important issue updates.
- **Feedback and Reopening:** Collect user feedback and support reopening unresolved issues.
- **Dashboard and Analytics:** Support maintenance monitoring and reporting.

## Issue Lifecycle

`Submitted → Acknowledged → Assigned → In Progress → Resolved → Closed`

Additional states may include Reopened, Rejected, Cancelled, and Escalated.

## System Actors

- **Student:** Reports issues, tracks progress, and provides feedback.
- **Faculty/Staff:** Reports and tracks campus-related problems.
- **Administrator:** Verifies issues, assigns technicians, and monitors progress.
- **Technician:** Works on assigned issues and updates their status.
- **Management:** Reviews reports and analytics for maintenance planning.

## System Architecture

CampusFix follows a three-tier architecture:

1. **Presentation Layer:** User interface for reporting and tracking issues.
2. **Application Layer:** Handles authentication, issue management, assignments, and notifications.
3. **Database Layer:** Stores users, issues, assignments, attachments, notifications, and status history.

## Repository Structure

```text
SOFTWARE_ENGINEERING/
├── SRS_IEEE.docx
├── activity diagram.pdf
├── class diagram.pdf
├── sequence diagram.pdf
├── state diagram.pdf
├── usecase diagram.pdf
└── README.md
```

## Future Enhancements

- AI-based issue classification and priority prediction.
- Duplicate issue detection.
- QR-code-based campus equipment reporting.
- Mobile application support.
- Integration with college ERP systems.

## Project Information

- **Project Name:** CampusFix
- **Domain:** Software Engineering
- **Project Type:** Academic Project
- **Documentation:** IEEE SRS and UML Diagrams

---

This repository documents the requirements and design of CampusFix as a centralized campus issue management system.
