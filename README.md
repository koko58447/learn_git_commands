# learn_git_commands

create push(new file)
======================
git init
git status
git add .
git commit -m 'commit_name'
git remote add origin url_link
git push -u origin branch_name

error refs
============
git remote (branch_name)
git config --global user.name 'git_user_name'
git config --global user.email 'git_email_name'
git commit -m 'commit_name'
git remote add origin url_link
git push -u origin branch_name

error publl
===========
git pull --rebase origin barnch_name

create push existing file
===========================
git status
git add .
git commit -m 'commit_name'
git remote add origin url_link
git push -u origin branch_name

respository delete
====================

rm -rf .git



create branch
==============
git branch branch_name

git branch --list

swicth or change branch
========================
git checkout branch_name

copy origin to new_branch
============================
git push --set-upstream origin new_branch_name
or
git push origin new_branch_name

create merge master and other branch
=======================================
git merge branch_name -m 'commit_name'
