mkdir: create folder
ls: files zeigen
cd: change directory

# git technology
git init: start git technologie in deinem projekt

we begin in master
we open a branch, so that we work inside, and no-one sees it

open a branch:
git checkout -b banner

if the branch exists:
git checkout banner

we work on the code, when we are happy
git status: to check which files we touched
git add . to tell git which files to track (. means all of them)

to commit (to make a screenshot, to save it on git) -> git commit -m 'create banner with background blue'

git status -> everything clean

we move to master: git checkout master

master has not yet the changes

we need to merge the changes from the branch to the master

git merge master banner
git merge [master] [name of the branch]

locally, we have in the master, the changes

but not on github

git push origin master
origin is the address of our github repo (our project on gitbub)
how to see our github addresses, where our code is hosted?
git remote -v

after pushing, the code is on github and since we are using github, our page is updated, without us doing absolutley anyhting





