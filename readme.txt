ssh-keygen -t rsa -C "rickzeng.love@gmail.com"

git config --global user.name "rickzeng.love"
git config --global user.email "rickzeng.love@gmail.com"

git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/rickzeng-love/gitrep.git
git push -u origin master
…or push an existing repository from the command line

git remote add origin https://github.com/rickzeng-love/gitrep.git
git push origin master
ssh -T git@github.com

git remote add origin git@github.com:rickzeng.love/gitrep.git

git remote rm origin

eval "$(ssh-agent -s)"

Creating a new branch is quick