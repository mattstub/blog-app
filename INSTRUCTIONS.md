# Development Process
Each working period will consist of informing your **REVIEWER** of what task you will be working on, you general plan to accomplish this task, and allow for a time to ask any questions you may have.  
  
This will allow the **REVIEWER** to make sure you are pointed in the right direction from the start.  
  
Each feature that is introduced will need to be on a different branch.  
  
## Git Workflow  
- Starting on master, pull down the latest changes from your remote repository on GitHub  
    ` git pull origin master `  
- Once changes are introduced to master, create a new branch to work on said feature  
    ` git checkout -b <feature-name> `  
- Utilize best practices to make our commits as you go, keep commits limited to necessary files.  
  - Do not use ` git add . `  
- Push your commits up to the remote repository on the applicable branch
    ` git push origin <feature-name> `
- Once a substantial portion of the feature is complete, or you would like some feedback, generate a **Pull Request**
  - Open GitHub and create a **Pull Reqest** from branch `<feature-name>` to `master`
  - As you continue to push up commits to GitHub the **Reviewer** can see each commit and give feedback as necessary
- Once the **Pull Request** is complete, tag a message with a mention to the **REVIEWER** so they can give feedback and review the changes
- Once the feature has been approved, it will be merged to master and be a live feature
