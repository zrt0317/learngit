Common GIT commands for rookies:

# After installation
$ git config --global user.name "Your Name"
$ git config --global user.email "email@example.com"

# Create local repository named learngit
$ mkdir learngit
$ cd learngit

$ git init

# Create files in local repo
$ git add (file_name)
$ git commit -m (comment_text)

# See status
$ git status
$ git diff (file_name)
$ git log
$ git reflog
$ cat (file_name)

# reset
$ git reset --hard HEAD~k


## Something else?
$ git checkout -- readme.txt
$ git diff HEAD -- readme.txt
$ git reset HEAD readme.txt

$ rm test.txt
$ git rm test.txt

## Repo on github
$ ssh-keygen -t rsa -C "youremail@example.com"
https://www.liaoxuefeng.com/wiki/896043488029600/898732864121440

# Repo on github
$ git remote add origin git@github.com:michaelliao/learngit.git
https://www.liaoxuefeng.com/wiki/896043488029600/898732864121440