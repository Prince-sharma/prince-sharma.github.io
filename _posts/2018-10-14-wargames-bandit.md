---
layout: post
title: Wargames Bandit level 0
subtitle: Bandit wargames overthewire
gh-repo: prince-sharma/prince-sharma
gh-badge: [star, fork, follow]
tags: [bandit, wargames, overthewire]
# image: /assets/images/OverTheWire/logo.png
---

![over the wire logo](/assets/images/OverTheWire/logo.png "Logo Title Text 1")

This and the upcoming few posts will be the solutions for **Bandit**  *wargames* form  **OverTheWire** .

## Level Goal

>The goal of this level is for you to log into the game using SSH.
>The host to which you need to connect is *bandit.labs.overthewire.org* , on port 2220.
>The username is **bandit0** and the password is **bandit0** . Once logged in, go to the Level 1 page to find out how to beat Level 1.

### Commands you may need to solve this level
>ssh

### Helpful Reading Material

>[Secure Shell (SSH) on Wikipedia](https://en.wikipedia.org/wiki/Secure_Shell)

>[How to use SSH on wikiHow](https://www.wikihow.com/Use-SSH)

## Write-up

If you have never heard of `ssh` before it's probably a good time to go through the links mentioned above or just google ssh and go through the basic `ssh` commands such as logging in into the remote computer, though I would suggest not to dig very deep since you'll be learning more and more as you progress through the levels :wink:

Now if you are as **noob** as me you would have ssh-ed without specifying port no like this:
`ssh bandit0@bandit.labs.overthewire.org`

but we have to give the specified port no since `bandit.labs.overthewire.org` doesn't uses port 22  ( which is the default port )  hence we need to specify port 2220 as below:
`ssh bandit0@bandit.labs.overthewire.org -p 2220`

that's it we can now proceed to Level 1





