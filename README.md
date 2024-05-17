# EERE Small Business Program

The EERE Small Business Program project is designed to support small businesses in the energy industry by automating the application and funding process. This project focuses on providing a seamless experience for both applicants and EERE staff.

## [Project Link](https://skillstorm70-dev-ed.develop.lightning.force.com/lightning/setup/SetupOneHome/home)

## User's Perspective

From the user's perspective, the system is designed to be intuitive and efficient. Here's a brief overview of the user experience:

### Applicant Experience:

- Applicants are redirected to a Web-to-Lead page to enter their information.
- Upon submission, they receive a confirmation page.

### EERE Staff Experience:

- EERE staff use the EERE Management Salesforce app to view captured leads.
- Leads are assigned to a queue, triggering automated processes such as lead assignment rules, automated emails, lead scoring, and escalation for manager approval if the score is above 6.

## Back End Processes

The back-end processes ensure smooth operation and data integrity through various automations, security measures, and data management practices:

### Automations:

- Three flows are created to manage Lead and Opportunity objects, triggered on record creation or update.
- Approval processes notify approvers and create tasks at each stage to facilitate the application lifecycle.

### Data Security:

- Org-Wide Defaults (OWD) are set to private.
- Minimal access profiles are created, with additional access granted through permission sets to ensure necessary data access only.

### Data Management:

- Customized standard objects such as Leads and Opportunities to fit the project's needs.

### Created specific record types:

- Lead Record Type: Captures necessary data for initial application stages.
- Opportunity Record Type: Tracks accepted applications through subsequent stages for review and approval.
