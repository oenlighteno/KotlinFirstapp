echo "# KotlinFirstapp" >> README.md

git init

git status

git add README.md

git commit -m "first commit"

git remote add origin https://github.com/oenlighteno/KotlinFirstapp.git

git push -u origin master

git pull

git config

git add .

git log

q

*for set git to auto replace CR and CRLF ("true" or "false" or "input")

https://stackoverflow.com/questions/1967370/git-replacing-lf-with-crlf

git config core.autocrlf

git config --global core.autocrlf false

git config --local core.autocrlf false

*How to exit git log or git diff?
https://stackoverflow.com/questions/9483757/how-to-exit-git-log-or-git-diff

You're in the less program, which makes the output of git log scrollable.

Type q to exit this screen. Type h to get help.