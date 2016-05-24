My-Practo-Diary
Day 1
GIT:
git init to initialise git repository
git status to know the status of our project(use it often)
git keeps track of file only if use the command git add
to store our changes in repository use git commit -m ""
git add '*.txt' stages all the text files irrespective of where they are present
git commit -m '' to commit changes
git log remembers the commits we have done so far
git log --summary for extra information
git remote add origin link(origin is remote name and link is repository url) this command adds our local repo to server ie link
The push command tells Git where to put our commits when we're ready, For example,pushing our local changes to our origin repo (on GitHub).
git push -u origin master -u remembers origin and master(no need to call it every time)
git pull origin and master to get a updated version of master
HEAD points to recent commit
git diff HEAD
git diff --staged
git reset filepath to unstage a file
git checkout --octocat.txt(changes repository to last committed)
git branch new-branch
git checkout octocat.txt(shifts to a branch)
Staged files are files ready to get committed
git add does staging
diff looks among staged files
checkout is used to switch among branches and master


