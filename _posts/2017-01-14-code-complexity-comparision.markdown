---
layout: post
title:  "Code Complexity Comparision"
date:   2017-01-14 20:12:04 +0330
---

*How hard a project can be to understand, maintain, refactor, and fix bugs?*

Well I've always spent some time on each project to get the intuition but after all it's just
my intuition and convincing others on that usually takes quite a time if it's negotiable at all.
Except how hard a project can be to start contributing, There are other important aspects too like
where are the most complexities lied on? and where are the most error prone parts of the code?

There are plenty of tools for each of these metrics and usually there results are impressive.
Here I compared my current company's project with the last two which tells me all the feeling
I've experienced about each one on them on how complex and hard they were:

| Company | Maintainability | Accessibility for new developers | Simplicity of algorithms | Volume | Reducing bug's probability |
| ------- | ----------------| -------------------------------- | ------------------------ | ------ | -------------------------- |
| X | 70.29 / 100 | 43.9 / 100 | 76.43 / 100 | 79.55 / 100 | 68.85 / 100 |
| Y | 57.71 / 100 | 38.65 / 100 | 50.71 / 100 | 69.68 / 100 | 65.57 / 100 |
| Current | 28.75 / 100 | 21.52 / 100 | 29.71 / 100 | 24.2 / 100 | 29.51 / 100|

X
![overview](code-complexity-comparision/x-overview.png "Overview")
![evaluation](code-complexity-comparision/x-evaluation.png "Evaluation")
![relations map](code-complexity-comparision/x-relations-map.png "Relations Map")

Y
![overview](code-complexity-comparision/y-overview.png "Overview")
![evaluation](code-complexity-comparision/y-evaluation.png "Evaluation")
![relations map](code-complexity-comparision/y-relations-map.png "Relations Map")

Current
![overview](code-complexity-comparision/current-overview.png "Overview")
![evaluation](code-complexity-comparision/current-evaluation.png "Evaluation")
![relations map](code-complexity-comparision/current-relations-map.png "Relations Map")
