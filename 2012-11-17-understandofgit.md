---
layout: post
title: "UnderstandOfGit"
description: ""
category: 
tags: [git]
---
{% include JB/setup %}
The basis concept in git is :
    * blob: the object to store the content of the file.
    * tree: the object to store the working files tree.
    * commit: the object to store the information about one commit,including the
      pointer to the tree which store the working tree, and description about
      the commit, and the pointer to the parent of the commit.
    * branch: a reference of a commit, it updates to point ot the new commit
      when a new commit is submitted.
    * tag: a reference of a commit, it points to the same commit permanently
      once initiated.

Git command is just used to manipulate these objects.     
