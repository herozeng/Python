Setting your username/email in git

git config --global user.name "herozeng"
git config --global user.email "herozeng322@gmail.com"

ssh -T git@github.com


Create a new repository on the command line

touch README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/herozeng/python.git
git push -u origin master

Push an existing repository from the command line

git remote add origin https://github.com/herozeng/python.git
git push -u origin master