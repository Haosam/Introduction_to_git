## This is my First Lesson on Git through Git Bash

#### Local git-ting
First, enter into a directory via Git Bash

Initialize the directory through
'''
git init
'''

If you want to add your username and email
'''
git config --global user.name "<NAME>"
git config --global user.email "<EMAIL>"
'''
To check the status of your files after you have edited any files
'''
git status
'''
To commit those files
'''
git add .
OR
git add <FILENAME>

git commit -m "<ENTER A MESSAGE>"
'''


#### Creating a new branch and working on it
Create a new Branch and merge with master branch
'''
git checkout -b <BRANCH_NAME>
git branch -v # Check all versions/commits
=> Do your file edits
git add .
git commit -m "<MESSAGE>"
# Once the above is done, the branch has the updated files, not the master
git checkout master
git merge <BRANCH_NAME>
'''

#### Working with Online gits
'''
# Either clone or add a new remote
git clone <LINK NAME>
# OR
git remote add origin <LINK NAME>

# Once you have commited your git, push it into the remote repository
'''
