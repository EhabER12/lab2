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
4- to list tags we use the command
git tag
5- to remove tag from local repo we use command
git tag -d v1.7
6-
to remove tag from remote repo we use command 
git push origin --delete v1.7