---
title: Push folder to Github 同步文件夹
description: To send the edited contents in the folder to the repository of Github.
pubDate: June 12 2025
categories:
  - Study
tags:
  - Blog
  - Code
badge: By Kevin ZOU
---

## Entrance
Go to the Explorer of Windows System  
Go to the folder  
Go to the address bar (Ctrl + L)  

Mouse: right-click
Select: bash here (We need to install "Git" software in advance)

## How to do?
Enter the codes below:
```
git add .
git commit -m "250612-1805"
git push
```
Before this, we need to connect the local "Git" with the remote repository through this:
```
git init
git remote add origin https://github.com/yourname/yourrepo.git
```
This address can be copied from our Github.
## Results
If no error message.
Now, the folder has been successfully copied to the remote repository on Github.