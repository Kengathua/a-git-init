# create a new repository on the command line
# SSH
echo "# a-git-init" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M master

git remote add origin git@github.com:Kengathua/a-git-init.git

git push -u origin master


# HTTP
echo "# a-git-init" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M master

git remote add origin https://github.com/Kengathua/a-git-init.git

git push -u origin master


# push an existing repository from the command line
# SSH
git remote add origin git@github.com:Kengathua/a-git-init.git

git branch -M master

git push -u origin master


# HTTP
git remote add origin https://github.com/Kengathua/a-git-init.git

git branch -M master

git push -u origin master
