### Always run 'git status' like your life depends on it



git init 
    Start a new Git repository in your current folder

git clone <repository-url>
    Make a local copy of a remote repository

git status
    See which files are staged, unstaged or untracked

git add <filename>
# or add everything
git add .
    Select the changes you want to commit

git commit -m "your commit message here"
    Save a snapshot of the changes you staged

git log
    See all the past commits

git branch <branch-name>
    Make a new branch off your current commit

git checkout <branch-name>
# or new way (Git 2.23+):
git switch <branch-name>
    Move to another branch

git push origin <branch-name>
    Send your commits to the remote repository

git pull
    Update your local branch with latest commits from remote