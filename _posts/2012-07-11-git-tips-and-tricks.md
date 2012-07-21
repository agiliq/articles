---
layout: post
title: Git Tips And Tricks
---

**Dheeraj:**

--branches flag on `git log` lists commits from all branches.

    git log --pretty=format:%s --since=1day --branches

**Dheeraj:**

I guess most of you know this. Adding git files by patch seems to be a good way of adding hunks to the staging area. Same with unstaging hunks. I used to do this using fugitive.vim, by doing vimdiff and "putting" desired hunks.

    git add -p
    git reset -p 

are your friends

**Shabda:**

Not git but github tip.

On any repo (or other tree page)

type "t" to start file finder and start typing to filter the list.
