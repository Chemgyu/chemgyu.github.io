---
title: Git and Github
author: MinGyu Choi
date: 2021-02-09 21:00:00 +0900
categories: [Programming, Github]
tags: [github]
math: true
mermaid: true
---

## What is git? Why we use it?
During our individual progrmming work, sometimes we need to 'track' our work. 
For example, assume that a program is making an error sign after a long period of editing. 
Because we didnot saved our intermediate files, we cannot find out the exact line where generates an error.
In order to prevent this kind of disaster, some people are saving their saving files in their local drive, or some kind of cloud drive. 
Individual local drive or cloud database might sufficient for novice programmers, however, for professional work or company job, memory requirements for saving whole job overflows individual available storage volume.
'Git' is saving this absurdity by providing 'snapshot' of my project frequently.
By exploiting Git's operations, programmers can efficiently saving their codes safely.
Moreover, Git system is quite efficient. Which means, Git is not saving the whole source code of programs, but storeing only the differeces(a.k.a. delta).
By implementing this, Git provides individual programmers a safe tracking system, guaranteeing programmers to come back any version of their source code.

This post is still being edited.

useful website : https://learngitbranching.js.org/?locale=ko