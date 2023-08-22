# Rules:

## GitHub Best Practices and Workflow Guidelines
Branching Strategy
Feature Branches: Always create a new branch for each feature or bug fix. Use descriptive names, include the Jira ticket ID for traceability.

### Proper branch name: feature/PROJ-123-add-user-authentication

Main Branches: The main branch is for production-ready code. No changes can be pushed directly to main. All changes should be merged via pull requests.

Development Branch: Use a development branch as a staging area for feature integration and testing. Create feature branches from and merge them back into this branch.

## Jira Integration
Ticket IDs: Include the Jira ticket ID in your branch names for easy cross-reference between code changes and tasks. This aids in tracking progress and linking code changes to specific requirements.

Moving Through Workflow: Update the Jira ticket status as you move through the development process (To-Do, Inprogress, Code Review, Done). This provides transparency about the progress of each task.

## Workflow Lifecycle
Backlog: These are tickets with very low priority, either unavailable for pickup at the moment, or requiring some discussions about their requirements. Please seek permission before taking up any of these tasks.

To-Do: Tickets in this status are waiting to be picked up by developers. Ensure that sufficient information is available before moving to the next stage.

In Progress: Assign the ticket to yourself, create a feature branch, and begin working on the task. Regularly update the Jira ticket to reflect your progress.

Code Review: Once your work is complete, create a pull request and assign a reviewer. Mention the Jira ticket ID in the pull request description for easy reference.

Done: Once the pull request passes code review, and any necessary revisions are made, the changes are merged into the development branch. Update the Jira ticket to mark it as "Done."

## Pull Requests
Descriptive Titles: Use clear and concise titles for pull requests. Include the Jira ticket ID and a brief description of the changes.

Detailed Descriptions: Provide detailed context and information about the changes made in the pull request description. Mention any related Jira tickets.

Review Etiquette: Reviewers should provide actionable feedback and suggestions. Approve the pull request only when satisfied with the code quality and functionality.

## Code Quality
Coding Standards: Follow the organization's coding standards and best practices. Write clean, well-documented, and maintainable code.

Main Branch
No Direct Pushes: Changes cannot be pushed directly to the main branch. This branch is reserved for production and deployment. All changes must go through the pull request process.

Team Lead Responsibility: Only the team lead is authorized to push changes to the main branch, typically after thorough testing and code review.

## Jira Board: https://consulting69.atlassian.net/jira/software/projects/KAN/boards/1
