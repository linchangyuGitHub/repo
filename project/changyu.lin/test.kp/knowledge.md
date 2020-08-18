---
title: This is a Knowledge Template Header
authors:
- lcytest
tags:
- knowledge
- example
created_at: 2020-08-13 00:00:00
updated_at: 2020-08-18 20:48:36.265194
tldr: This is short description of the content and findings of the post.
---

```python
import os
a = os.getcwd()
a
# res = os.path.exists("~/scp_file")
# res
```




    '/home/changyu.lin'




```python
res =os.path.expanduser("~/scp_file")
res1
```




    '/home/changyu.lin/scp_file'




```python
res = os.path.isabs("k_r_lcy")
res
```




    False




```python
res = os.path.abspath("k_r/repo")
res
```




    '/home/changyu.lin/k_r/repo'




```python

```