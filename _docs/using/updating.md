---
title: Updating
category: categoryHere
order: 4
---

[![GitHub stars](https://img.shields.io/github/stars/Narehood/DocTemplate.svg)](https://github.com/Narehood/DocTemplat/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Narehood/MusicBot.svg)](https://github.com/Narehood/DocTemplat/network)
[![Python version](https://img.shields.io/badge/python-3.5%2C%203.6%2C%203.7-blue.svg)](https://python.org)

> 
> - Windows: 
> - Mac: 
> - Linux: 
>


* **Linux/MacOS**: 
* **Windows**: 
* **Other**: 

## Manual update

```sh
git reset --hard  # Reset your current working directory
git pull  # Pull the latest changes from Git
```

### Common problems
#### error: Your local changes to the following files would be overwritten by merge
This indicates that you are trying to pull the latest updates from Git, but you've made changes to the bot's source files yourself. As a result, Git struggles to merge your changes with the bot's changes. To fix this, stash your changes first by running `git stash`, then run `git stash pop` after pulling.

Alternatively, discard your local changes by running `git reset --hard`.

> We do not support modification. If you are having issues updating because you have edited the bot's files, this is the most guidance you will get.

#### fatal: Not a git repository
This indicates that you have not installed the bot using Git. To be able to update, you need to install the bot using Git by following the guides on this site.

#### fatal: unable to access 'https://github.com/Narehood/DocTempalte.git' SSL certificate problem: self signed certificate in certificate chain
Try disabling your antivirus. Some antivirus software (such as Kaspersky Internet Security) is known to interfere with git.
