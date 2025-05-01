# Git Basic Commands


1. Start a new Git repository in your current folder <br>
git init

2. Make a local copy of a remote repository <br>
git clone <repository-url>

3. See which files are staged, unstaged or untracked <br>
git status

4. Select the changes you want to commit <br>
git add <filename>
git add . (or add everything)

5. Save a snapshot of the changes you staged <br>
git commit -m "your commit message here"

6. See all the past commits <br>
git log

7. Make a new branch off your current commit <br>
git branch <branch-name>

8. Move to another branch <br>
git checkout <branch-name>
git switch <branch-name> (or new way (Git 2.23+))

9. Send your commits to the remote repository <br>
git push origin <branch-name>

10. Update your local branch with latest commits from remote <br>
git pull


## Pro tips
Always run 'git status' like your life depends on it
