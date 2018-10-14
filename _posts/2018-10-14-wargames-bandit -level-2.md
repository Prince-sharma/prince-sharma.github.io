---
layout: post
title: Bandit level 1 ~> level 2
subtitle: Bandit wargames overthewire
gh-repo: prince-sharma/prince-sharma
gh-badge: [star, fork, follow]
tags: [bandit, wargames, overthewire]
# image: /assets/images/OverTheWire/logo.png
---

![over the wire logo](/assets/images/OverTheWire/logo.png "Logo Title Text 1")

## Level Goal

>The password for the next level is stored in a file called - located in the home directory


### Commands you may need to solve this level
>ls, cd, cat, file, du, find

### Helpful Reading Material

>[Google Search for “dashed filename”](https://www.google.com/search?q=dashed+filename)

>[Advanced Bash-scripting Guide - Chapter 3 - Special Characters](http://tldp.org/LDP/abs/html/special-chars.html)


## Write-up

Firstly I tried `bandit1@bandit:~$ cat -` but that doesn't work since it treats it as a synonym for stdin, to get around this we can prefix the filename with a path `./-` , hence `bandit1@bandit:~$ cat ./-` works 

#### Password for bandit2 : `CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9`




