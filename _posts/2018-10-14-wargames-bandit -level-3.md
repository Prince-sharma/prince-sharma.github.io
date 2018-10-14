---
layout: post
title: Bandit level 2 ~> level 3
subtitle: Bandit wargames overthewire
gh-repo: prince-sharma/prince-sharma
gh-badge: [star, fork, follow]
tags: [bandit, wargames, overthewire]
# image: /assets/images/OverTheWire/logo.png
---

![over the wire logo](/assets/images/OverTheWire/logo.png "Logo Title Text 1")

## Level Goal

>The password for the next level is stored in a file called **spaces in this filename** located in the home directory


### Commands you may need to solve this level
>ls, cd, cat, file, du, find

### Helpful Reading Material

>[Google Search for “spaces in filename”](https://www.google.com/search?q=spaces+in+filename)


## Write-up

first, we check the contents of the current directory using `ls` command, which lists a file whose name has spaces. I simply used `bandit2@bandit:~$ cat spaces\ in\ this\ filename`  , here this can be achieved either by tab completion or using  `\` as an escape character. 

#### Password for bandit3 : `UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK`




