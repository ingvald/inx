---
title: software development priorities, values
date: '2016-12-06'
tags: [quality, code]
description: readability is perhaps the most important long-term quality aspect of code
permalink: posts/{{ title | slug }}/index.html
---

in that order...

* readability
    * try to let every change make it easier, quicker to understand, learn, remember
* maintainability
* changeability, evolutionary design
    * try to let every change make it cheaper to modify in the future
  * ([including evolutionary db design](http://martinfowler.com/articles/evodb.html))

.
.
.

* writeability, speed of writing new code
  * [code is read much more often than it is written](https://devblogs.microsoft.com/oldnewthing/?p=27343)
    * [software devs spend most of their time trying to understand code](https://blog.codinghorror.com/when-understanding-means-rewriting/)
