---
layout: post
title:  "Code Complexity Comparision"
date:   2017-01-14 20:12:04 +0330
---

**How hard a project can be to be understood, maintained, refactored, and/or fixed bugs?**

Well I've always spent some time on each project to get the intuition but after all it's just
my intuition and convincing others usually takes quite a time if it's negotiable at all.
Except how hard a project can be to start contributing, there are other important aspects too like
where are the most complexities lied on? and where are the most error prone parts of the code?

There are plenty of tools[^1] for each of these metrics[^2] and usually there results are impressive.
Here I compared 3 companies' projects with each other which tells me all the feelings I've experienced
about each one on them:

| Metrics                              | Company X   | Company Y   | Company Z   |
| :----------------------------------- | :---------: | :---------: | :---------: |
| **Maintainability**                  | 70.29 / 100 | 57.71 / 100 | 28.75 / 100 |
| **Accessibility for new developers** | 43.90 / 100 | 38.65 / 100 | 21.52 / 100 |
| **Simplicity of algorithms**         | 76.43 / 100 | 50.71 / 100 | 29.71 / 100 |
| **Volume**                           | 79.55 / 100 | 69.68 / 100 | 24.20 / 100 |
| **Reducing bug's probability**       | 68.85 / 100 | 65.57 / 100 | 29.51 / 100 |

---
---

# Company X
[x-overview]: {{ site.url }}/assets/code-complexity-comparision/x-overview.png "Overview"
[x-evaluation]: {{ site.url }}/assets/code-complexity-comparision/x-evaluation.png "Evaluation"
[x-relations-map]: {{ site.url }}/assets/code-complexity-comparision/x-relations-map.png "Relations Map"

[![overview][x-overview]{: width="200px"}][x-overview]{:target="_blank"}
[![evaluation][x-evaluation]{: width="200px"}][x-evaluation]{:target="_blank"}
[![relations-map][x-relations-map]{: width="200px"}][x-relations-map]{:target="_blank"}

# Company Y
[y-overview]: {{ site.url }}/assets/code-complexity-comparision/y-overview.png "Overview"
[y-evaluation]: {{ site.url }}/assets/code-complexity-comparision/y-evaluation.png "Evaluation"
[y-relations-map]: {{ site.url }}/assets/code-complexity-comparision/y-relations-map.png "Relations Map"

[![overview][y-overview]{: width="200px"}][y-overview]{:target="_blank"}
[![evaluation][y-evaluation]{: width="200px"}][y-evaluation]{:target="_blank"}
[![relations-map][y-relations-map]{: width="200px"}][y-relations-map]{:target="_blank"}

# Company Z
[z-overview]: {{ site.url }}/assets/code-complexity-comparision/z-overview.png "Overview"
[z-evaluation]: {{ site.url }}/assets/code-complexity-comparision/z-evaluation.png "Evaluation"
[z-relations-map]: {{ site.url }}/assets/code-complexity-comparision/z-relations-map.png "Relations Map"

[![overview][z-overview]{: width="200px"}][z-overview]{:target="_blank"}
[![evaluation][z-evaluation]{: width="200px"}][z-evaluation]{:target="_blank"}
[![relations-map][z-relations-map]{: width="200px"}][z-relations-map]{:target="_blank"}

The beauty lies on comparison. More red circles means much harder to maintain and collaborate, in addition to that,
project suffers from bad and complex design. It also implies refactoring is not taken as much serious as it should
be and the only converging thing is technical debt.

It can also shows company's moral for example does this company put time for paying code's debt or all features are
in rush and should be delivered as fast as possible by whatever quality it gains (feature-rich) and lots of other
things.

---
[^1]: I used [PhpMetrics](https://github.com/phpmetrics/PhpMetrics)
[^2]: e.g. [cyclomatic complexity](https://en.wikipedia.org/wiki/Cyclomatic_complexity)