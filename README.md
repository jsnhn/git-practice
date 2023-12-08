# Git Practice

Here are some commands for Git CLI:
1. To create a local Git repo, we run `git init` 
2. To link our local Git repo with a remote Github repo, we run this command: `git remote add origin <link to remote repo>`
3. When we've made changes to our Git repo, the command to add the files and folders that have been changed to the staging area is `git add .`
4. Once all the changes are in the staging area, this is the command to create a commit that records those changes: `git commit -m 'message describing changes'`
5. to push all of our local commits that are not currently in the remote repo, we run this command: `git push <remote repo alias> <local branch name>` Following this patter, we will be using `git push origin main`

If you would like to check if there are any unstaged changes or any staged changes waiting to be made into a commit, you can run `git status`

After forking a project, on Github, you can do the following: 
1. Clone the forked remote to your local maching by running `git clone <link to remote forked repo`
2. If you would like to receive any updates from the orignal remote repo that you forked, set the original remote as your upstream remote with the command `git remote add upstream <link to original remote>`
3. When you need to retrieve updates from the original remote, you can use the pull command `git pull <remote alias name> <remote branch name>`. Following this pattern, we will be using `git pull upstream main`.
4. Once you've pulled all of the original remote's commits to your local Git repo, you can push those new commits to your own forked remote with `git push origin main`

If you need to view which remote repos are connected to your local Git repo, you can use the command `git remote -v`
