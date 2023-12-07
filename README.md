# Git Practice

Here are some commands for Git CLI:
1. To create a local Git repo, we run `git init` 
2. When we've made changes to our Git repo, the command to add the files and folders that have been changed to the staging area is `git add .`
3. Once all the changes are in the staging area, this is the command to create a commit that records those changes: `git commit -m 'message describing changes'`
4. To link our local Git repo with a remote Github repo, we run this command: `git remote add origin <link to remote repo>`
5. to push all of our local commits that are not currently in the remote repo, we rin this command: `git push <remote repo alias> <local branch name>` Following this patter, we will be using `git push origin main`