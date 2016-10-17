# hello-world

https://help.github.com/articles/set-up-git/
https://git-scm.com/book/en/v2/Git-Basics-Recording-Changes-to-the-Repository


git config --global user.name "Your Name Here"
git config --global user.email "your_email@youremail.com"

git init
git remote add origin https://github.com/username/myproject.git
git remote -v

git clone https://github.com/username/repository
git status
git diff

git commit
git commit -a -m 'added new benchmarks'


git push

// remove
git rm

// log
git log

//undo
git reset HEAD CONTRIBUTING.md or git checkout -- CONTRIBUTING.md


// remote update
git push origin master
git fetch origin master