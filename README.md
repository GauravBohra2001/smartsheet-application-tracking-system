# Smartsheet Application Tracking & Automation System

This project demonstrates the design and implementation of an application tracking system using Smartsheet, focused on workflow automation, operational visibility, and process efficiency for administrative teams.

The system is designed to manage applications end-to-end, automate key communications, and provide real-time insights through dashboards.

---

## Problem Statement

Administrative teams often rely on spreadsheets and manual follow-ups to manage application workflows, leading to:

- Missed deadlines
- Manual email communication
- Limited visibility into application status
- Data inconsistencies and access control issues

This project addresses these challenges by using Smartsheet as a structured system of record with built-in automation.

---

## System Overview

The solution consists of:

- A centralized application tracking database
- Automated workflows for notifications and reminders
- A real-time administrative dashboard
- Documented processes for scalability and onboarding

---

## Application Tracking Database

**Sheet:** `Application_DB`

Each row represents a single application. Key fields include:

- Application ID
- Student Name & Email
- Application Type
- Status (Submitted, Under Review, Approved, Rejected)
- Assigned Reviewer
- Submission Date
- Review Due Date
- Decision Date

The sheet acts as the single source of truth for all workflows and reporting.

---

## Workflow Automations

### 1. Approval Notification

- **Trigger:** Status changes to `Approved`
- **Action:** Automatically sends an email notification to the applicant
- **Purpose:** Eliminates manual approval emails and ensures timely communication

### 2. Review Due Date Reminder

- **Trigger:** Review Due Date is reached
- **Condition:** Status is `Under Review`
- **Action:** Sends an automated reminder to the assigned reviewer
- **Purpose:** Prevents delayed reviews and improves SLA compliance

---

## Administrative Dashboard

A dynamic dashboard provides real-time insights, including:

- Total number of applications
- Breakdown of applications by status
- List of overdue reviews
- Recent application submissions

The dashboard enables administrators to monitor workload and identify bottlenecks quickly.

---

## Access Control & Data Integrity

The system is designed with role-based access in mind:

- Applicants submit data via forms (no sheet edit access)
- Reviewers update status and notes only
- Administrators maintain full control

This ensures data security and compliance with organizational policies.

---

## Documentation & Maintainability

- Workflow logic is clearly defined and easy to modify
- Column definitions and automation triggers are documented
- The system is designed to be easily extended with additional workflows or integrations

---

## Future Enhancements

- Integration with email platforms and collaboration tools (e.g., Outlook, Slack)
- Additional reminder workflows for overdue applications
- Enhanced dashboard visualizations for trend analysis

---

## Tools & Technologies

- Smartsheet
- Smartsheet Automation & Alerts
- Smartsheet Dashboards & Reports

---

## Key Takeaways

This project demonstrates:

- Designing database-like systems using Smartsheet
- Implementing conditional and date-based automations
- Translating business workflows into scalable operational systems
- Building dashboards for real-time decision-making

---

## Project Impact

- Aligns perfectly with Smartsheet & Automation Specialist role requirements
- Demonstrates hands-on automation experience, not just theoretical knowledge
- Reflects real-world university operations scenarios
- Provides concrete talking points for technical interviews
