# practice-repo

1. Create new repository (github.com/new), make sure to make public, add a README.md

2. Clone (big green button, "CODE") your repo using the HTTPS or SSH(if you have that set up) into a folder on your computer. "git clone urlString"

3. Adding collaborators. Settings > Manage Access > Invite collaborators

4. Set Rules. Settings > Branches > Add Rule > set branch name > select : 'Require pull request reviews before merging' AND 'Include administrators' > create

5. Set up a project, "basic kanban"

6. Create issues and assign to project (don't worry about creating them all at once, start with the basics)

6. Pushing our branch. 

 - "git status"
 - "git add ."
 - "git commit -m 'message' "
 - "git status"
 - "git pull origin main"
 - "git push origin <branchName>"

 7. Complete the pull request. Go to "pull requests", click green button that says "pull request", assign to project and assign reviewers.

 ## How to view and run code from someone elses branch. This will be useful when reviewing a "pull request". ##

 - "git fetch"
 
 - "git checkout -b <branchName> origin/<branchName>"

 