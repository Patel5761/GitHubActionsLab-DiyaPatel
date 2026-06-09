# GitHubActionsLab-DiyaPatel
Workflow 1 - Job Dependency Workflow

In this workflow, the jobs Build, Test, and Deploy will run in a particular order using the needs keyword to showcase the dependency of jobs.

Workflow 2 - Multilingual Jobs Workflow

This workflow highlights running independent jobs on Ubuntu, Windows, and macOS operating systems simultaneously.


needs: It is used to set up dependency for jobs, and control the sequence of execution.

env: This is used to set environment variables that are available across multiple jobs and steps.

Challenges Encountered: One difficulty encountered was finding the folder ".github/workflows" and linking up the local repository to GitHub, which was sorted out through the use of Files view and Git.
