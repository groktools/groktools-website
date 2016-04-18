---
layout: post
title:  "whyCommit"
img: img/portfolio/submarine.png
icon: "&#xf1d3;&#xf128;"
modalID: modalWhyCommit
category: Tools
---

Add a reason for your change in the commit message

# Introduction
**whycommit** is a simple addition to your git workflow - it adds a template for your commit messages that helps you to guide future readers so that they understand your change better.

As found by [Maalej et al](https://mobis.informatik.uni-hamburg.de/wp-content/uploads/2014/06/TOSEM-Maalej-Comprehension-PrePrint2.pdf) (page 19):

> More than half of respondents agreed that they encounter problems at least weekly due to missing knowledge about “why was this code implemented this way”, “what was the developer’s intention when writing this code”.

`whyCommit` helps to bridge this gap and includes:

* A commit message template (`whycommit-template.txt`) that requires the author of the change to answer this question for future readers to grok.
* A bash/bat shell script to install the message template for one repo or for all of them.
* A bash/bat shell script to install a pre-commit hook preventing commits without a Why section (with an escape hatch for "small" commits detailed below).

Github: [https://github.com/groktools/whycommit](https://github.com/groktools/whycommit)
