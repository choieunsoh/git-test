# Front-End Web UI Frameworks and Tools: Bootstrap 4

### Coursera: https://www.coursera.org/learn/bootstrap-4

This repo is a part of self-learning at Coursera. I learned the basics of Git, Node and NPM commands.

### Git Resources

For good tutorials and ressources for Git and GitHub, I'd suggest the following:

- The [Pro-Git book](http://git-scm.com/book/en/v2) by Scott Chacon available on the git website.
- The [Try Git website available on GitHub made by CodeSchool](https://docs.github.com/en/get-started/quickstart/set-up-git)
- Or you can try the [Git Immersion](https://gitimmersion.com/)
- If you're still hungry after this, there is a good list of other [git stuff](https://www.webfx.com/blog/web-design/git-tutorials-beginners/) here.

[ref](https://stackoverflow.com/questions/18624255/block-other-users-on-github-from-editing-my-repos-without-paying-for-private-rep)

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

# push
git push -u origin main

# clone
git clone <url>

```

# Node.js

```bash
# version
node -v
npm -v

# init
npm init

```
