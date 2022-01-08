# git

```bash
git --version
git config --global user.name "Kiattipong Kamonrat"
git config --global user.name "marsimadz@hotmail.com"
git config --list
git config --global core.pager cat
# type q to exit git command

git init

# change branch name
git checkout master
git branch -m main

# change default branch
git config --global init.defaultBranch

# or init with branch name
git init --initial-branch=main
git init -b main

# add to staging area
git add .

# commit the changes to git repo
git commit -m "message"

# view a breif logs
git log --oneline
# view full log
git log

# rollback
git checkout <commit-id> <filename>

# remote repo
git remote add origin <url>


```
