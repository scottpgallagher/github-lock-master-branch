# github-lock-master-branch
Overview:
The purpose of this diagram is to show the workflow that one would follow for performing a few actions on new repositories within a new GitHub organization.

1. Lock master branch when a new repository is created. This is to ensure best practices are followed and pull requests are being made for committing to your master branches
2. Create a notification via a issue within newly created repository


Enhancements:
1. Check the master branch isn't empty
2. Verify the master branch can't be committed to
3. Additional notifications (ie Slack notification)
4. Add code to Jenkinsfile to perform API actions
