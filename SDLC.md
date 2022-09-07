
This document describes the steps that will be followed throughout each project process and the documentation required.
it will be the primary reference for team leaders, project managers, and product managers.

## Technical proposal
Analyze the project specification and business needs, then provide a technical proposal for the client
**```If the project is internal then we skip the proposal and move to the planning.```**

**Documents**
* Technical Proposal.

## Planning
use JIRA software for the planning phase, there you can define the project roadmap and assign tasks with every phase

**Documents**
* Project Roadmaps.
* System Definition.

**Tools**
* Jira.

**Note**: It is strongly recommended to connect the client to the JIRA project space, for better communication and keep updated with the project progress.

## Analysis
* Define the system users.
* Define the system's functional & non-functional requirements using the requirements document.
* Define where/when the system will be used.
* Make a use-case diagram.
* Make a use-case scenario.
* Define the project Scope.
* Define the project risks using the risk assessment document.
* Design the Database using the Database design document.
* Design the infrastructure using the project infrastructure document.
* Define the system architecture.
* Design the system architecture using the Design and Architecture document.
* Define the GitHub project type (repository/organization).
* Define the development methodology.
* Setup the development environment (folder structure, base code, etc..).

**Documents**
* Analysis Document.
* Project Infrastructure.
* Design and Architecture.
* Database Design.

**Tools**
* Jira.
* Microsoft Visio.

## Design
* Design the wireframe.
* Design the UI.
* Design the UX.

**Documents**
* User Experience Design.
* Wireframe Design.

**Tools**
* Microsoft Visio.
* Jira.

## Development
The development phase will be managed using Jira software, the project manager is responsible for assigning tasks to the team members and delivering the software before the deadline.

**Documents**
* API Documentation.
* Source Code Documentation.

**Tools**
* Jira.
* Github.
* Cloudflare.
* Heroku.

## Testing
* Use eslint for implementing coding style.
* Use security frameworks to scan the application vulnerabilities.

**Documents**
* Testing and Quality Assurance.
* End-User Documentation.
* System Admin Documentation.

**Tools**
* Jira.

## Deployment
while hosting the project on the GitHub platform, we will use two main branches (production + staging), the staging branch will be used for testing purposes, while the production branch will be for final results.
the client can only access the production branch.