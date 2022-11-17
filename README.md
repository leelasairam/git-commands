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

** Git Branch **
```git
git branch (to view all branches)

git branch new-feature (to create new branch)

git branch -D new-feature (to delete branch)

git checkout new-feature (to navigate other branch in repository)

git checkout -b new-feature (use this command to create a branch and navigate to that particular branch)

```
