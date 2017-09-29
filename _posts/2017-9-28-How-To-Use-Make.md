---
layout: post
title: How to use Make
tags: ["tutorial", "software"]
---

### Make Structure

```
target: prerequisites
[tab] recipe (commands)
```

* A `target` is usually the name of a file that is generated by a program; examples of targets are executable or object files.

* A `prerequisite` is a file that is used as input to create the target. A target often depends on several files.

* A `recipe` is an action that make carries out. A recipe may have more than one command, either on the same line or each on its own line. 

Please note: ```you need to put a tab character at the beginning of every recipe line! This is an obscurity that catches the unwary. ```
