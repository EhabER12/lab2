1- to delete branch in local repo we use the command
git branch -d dev
git branch -d test
2- to delete branch from the remote repo we use the command
git push origin --delete dev
git push origin --delete test
3- to checkout to another branch without commit the changes we use the command
git stach
git checkout branchName
if you want to reverse the changes use
git stash pop