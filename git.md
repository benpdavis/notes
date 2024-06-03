#Git default configs
git config --global init.defaultBranch main
git config --global user.name "benjamin"
git config --global user.email benjaminpeterdavis@outlook.com

##Committing folder contents from disk to repo
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/benpdavis/REPOSITORYNAMEGOESHERE.git
git push -u origin main

##GIT fix commit message
git commit --amend
##PUSH fixed message if already pushed to repository
git push --force-with-lease origin main