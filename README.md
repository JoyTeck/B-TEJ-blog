# B-TEJ-blog

## Initial Set up
This section describes the initial setup of the project
- Clone repo: `git clone git@github.com:JoyTeck/B-TEJ-blog.git`
- Move into directory: `cd B-TEJ-blog`
- Create your own branch: `git branch <branch_name>` replace `<branch_name>` with ur preferred name
- Switch to your new branch: `git switch <branch_name>`
- Start working on your section(s) by using ur preferred editor.

## Pushing branch to github
This section contains steps after you are done working on ur section in your branch.
- Add changes: `git add .`
- Commit changes: `git commit -m "Your commit message"`
- Push branch: `git push origin <branch_name>`
- Create pull request and merge: Go to github and create pull request, then merge.
- Notify the team after that or If there is any conflict, let them know before you take any technical step.

## Subsequent Modifiation
Tis section contains steps on how to do further modifications to the project (After your first push of your branch), Before you start another work on the project.
- Switch to main branch: `git switch main`
- Pull latest changes: `git pull`
- Switch back to your branch: `git switch <branch_name>`
- Check for updates: `git pull`
- Start working on your branch
When you are done, repeat [Pushing branch to github](#pushing-branch-to-github) again.