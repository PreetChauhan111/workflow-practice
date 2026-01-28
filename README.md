# workflow-practice
This Repository includes many workflow from basic to advance level which helps you to understand yml and workflows in depth

# Task 1

Goal:
Create a workflow that runs manually using workflow_dispatch.

Requirements:

Trigger: workflow_dispatch

Runner: ubuntu-latest

Job name: hello-ci

Steps:

Checkout the repository

Print:

Hello GitHub Actions
Repo: <repository-name>
Actor: <who triggered the workflow>
Workflow: <workflow name>


Use GitHub context variables (github.*)

No hardcoding values

Constraints:

Single job

No secrets

No matrix

No deployment

