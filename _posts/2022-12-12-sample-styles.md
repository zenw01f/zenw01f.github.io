---
title: "Sample add'l layout"
excerpt_separator: "<!--more-->"
last_modified_at: 2022-12-22T20:48:00-08:00
categories:
tags:
toc: true
toc_label: "Part 2 Contents"
toc_icon: "cog"
---

# Using .notice with different box colors
## Notice box with --info
**INFO:** Be sure to remove `/docs` and `/test` if you forked Minimal Mistakes. These folders contain documentation and test pages for the theme and you probably don't want them littering up your repo.
{: .notice--info}

## Notice box with --warning
**WARNING:** putting a single backticks will yeild: `Unknown tag 'include_cached'` 
{: .notice--warning}

## Notice box with --danger
**DANGER:** putting a single backticks will yeild: `Unknown tag 'include_cached'` 
{: .notice--danger}

# Code Boxes
using 3 ticks "```" to start and end a code box.
put the code type after the first set of ticks for syntax highlighting

```python
import os
print("hello world")
```