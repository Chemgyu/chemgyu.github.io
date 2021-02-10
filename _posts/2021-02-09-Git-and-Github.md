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
git
: Git is a distributed version-control system for tracking changes in any set of files, origianlly designed for coordinating work among programmers cooperating on source code during software development.[Wiki](https://en.wikipedia.org/wiki/Git)

As you can see in the definition of 'git,' git is a system for<br>
1. Tracking changes in any set of files
2. Facilitating coordinating work among programmers cooperating during software development.
<br>
# Git for tracking my work
During our individual progrmming work, sometimes we need to 'track' our work. For example, remind a situation that a program is making an error sign after a long period of editing. Because we did not saved our intermediate files, we cannot find out the exact line where is generating an error; which is an awful disaster.
<br>
In order to prevent this problem, some people are saving their intermediate files in their local drive, or cloud drive. Individual local drive or cloud database might sufficient for novice programmers, however, for professional work or company job, memory requirements for saving whole job overflows individual available storage volume. Moreover, frequently updating and storing files is quite cumbersome.
<br>
'Git' is providing a useful solution for this problem by providing 'snapshot' of my project frequently. After we 'commit' our source codes after meandingful changes, 'snapshots' of our source codes are automatically stored in server; whenevere we want, we can access to these files and we can browse previous versions.
<br>
# Git for cooperating workplaces
Unlike small-sized individual projects, big programs usually implemented in companies or universities are progressed by multiple programmers. The biggest problem in this cooperation system is a 'synchronization.' Assume that a project consists of two individual parts, you and your colleage is processing each part. After a long period of processing, your team is merging each results with a hope of great productivity. However, sometimes, because of incompatibility between two codes, a whole source code does not work quite well.
<br>
Likewise, in cooperation development, several additional problems emerge. In addition to synchronization, as aforementioned before, maybe one malicious programmer can deliberately jam your work. To prevent this possible perils, Git provides an efficient tool to manage progresses of the whole project.
<br>
Because Git is presenting every changes of the project and details, anyone can see the flow of the project; every individual participating in project can easily download and apply other people's result in their code simultaneously. In addition, if an error emerges, project members can track upward to find a wrong code. Moreover, if a malicious programmer deliberately erase some core part of the project, we also can monitor who, when, and where he/she effaced. 
<br>
# Git for effieicnt storage
There are many other storage system we can use for these reasons. However, we should use 'git' system, because it is an efficient tool for accomplishing aforementioned functions. Git is not saving the whole source code of programs, as an individual programmer often does, but they store only the differences(delta). Because they are storing only changed parts in their memory, users and servers can efficiently manage data.
<br>
Furthermore, because of this feature, git presents changes of the source code with visually attractive manner. By using git and their related programs, we can more easily manage our sorece codes more efficiently and securely.

This post is still being edited.

useful website : [learnbranching](https://learngitbranching.js.org/?locale=ko)
