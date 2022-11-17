# git-commands

## Flow ##

1. Go to folder location

2. git init

3. git add . (It adds all files in a folder)

   OR git add public/index.html (adds specific file in a folder)

   OR git add public/index.js public/index.html (to add multiple files)
   
   OR git add *public/.txt (pattren to add all .txt files)

4. git commit -m "First Commit"

5. git remote add origin https://github.com/leelasairam/my-links.git

6. git push -u origin master

## After Edit ##

1. git status

2. git add .

3. git commit -m "Second Commit"

4. git push -u origin master

**Git Branch**

```git
git branch (to view all branches)

git branch new-feature (to create new branch)

git branch -D new-feature (to delete branch)

git checkout new-feature (to navigate other branch in repository)

git checkout -b new-feature (use this command to create a branch and navigate to that particular branch)

```
**other**
```
git commit -am "commiting without staging (git add .)"

git ls-files (to know files in staging area)

git rm public/index.css (to remove unwanted files)

git mv public/index.md index.html (to change the path)
In .gitignore,
to add file - index.html
to add folder - public/
to add file pattren - *.txt

git rm --cached -r public/ (to remome folder from stage or index)

git diff --staged (to view differences in current staged files vs prev comited files)

git diff --unstaged (to view differences in unstaged files vs prev comited files)

git log (to view all commits)

git show HEAD~1 (to view what changes are done in prev commit. We can increase the number to much back)

git restore --staged index.html (to unstage the file from stage)

git restore index.js (to discard the local changes)

git restore --source=HEAD~1 public/index.html (Restoring a file from earlier version)

To create a local folder of other repository, we have to use the following command:
mkdir [directory- name]
cd [directory- name]
git clone [URL]

git log –graph –pretty=oneline (to make logs prettier)

git stash (command can be used when we want to save our work without staging or committing the code to our Git repository and want to switch between branches)

git merge new-feature

git fetch (When we use the command git fetch, Git gathers any commit from the target branch that does not exist in our current branch and stores it in our local repository. However, it does not merge it with our current branch.)
This is particularly useful when we need to keep our repository up to date but are working on something that might break if we updated our files. To integrate the commits into our master branch, we use merge. It fetches all of the branches from the repository. It also downloads all the required commits and files from another repository.

git pull origin master (pulls everthing from remote repository and updates local repository) 
```
