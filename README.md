---
title: Homework1
name: Chunze Liu
---

## HW1
The first homework, I saw some video in Youtube to learn Git, and then I starting it.

## Download Git and set my email and name
Download Git and sign a account in GitHub
Then create a README.md
```bash
echo "# HW1" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/15042295553/HW1.git
git push -u origin master

git config --global user.name "Chunze-Liu"
git config --global user.email "15042295553@163.com"
```
create a readme.txt index.html index.css
```bash
git add readme.txt
git commit
git add readme.txt
git log
touch index.css
git add index.css




