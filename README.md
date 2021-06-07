# practice-repo

1. Create new repository (github.com/new), make sure to make public, add a README.md

2. Clone (big green button, "CODE") your repo using the HTTPS or SSH(if you have that set up) into a folder on your computer. "git clone urlString"

3. Adding collaborators. Settings > Manage Access > Invite collaborators

4. Set Rules. Settings > Branches > Add Rule > set branch name > select : 'Require pull request reviews before merging' AND 'Include administrators' > create

5. Set up a project, "basic kanban"

6. Create issues and assign to project (don't worry about creating them all at once, start with the basics)

7. Pushing our branch. 

 - `git status`
 - `git add .`
 - `git commit -m 'message'`
 - `git status`
 - `git pull origin main`
 - `git push origin <branchName>`

 8. Complete the pull request. Go to "pull requests", click green button that says "pull request", assign to project and assign reviewers.

 ## How to view and run code from someone elses branch. This will be useful when reviewing a "pull request". 

 1. `git fetch`
 
 2. `git checkout -b <branchName> origin/<branchName>`

 ## How to update branch when another branch is merged before yours 

 If you have made changes make sure to commit before you pull or you will lose them.

 1. `git pull origin main`

 2. resolve conflicts

 3. `git add .`

 4. `git commit -m 'message'`

 5. `git pull origin main`

 6. `git push origin <branchName>`