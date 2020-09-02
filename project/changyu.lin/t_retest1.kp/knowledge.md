---
title: This is a Knowledge Template Header
authors:
- lcytest
tags:
- knowledge
- example
created_at: 2020-08-13 00:00:00
updated_at: 2020-09-02 19:43:12.152533
tldr: This is short description of the content and findings of the post.
---

```python
print(1)
```

```python
import os
```

```python
p = os.popen("sdsds")
if p.close() is not None and p.close() > 0:
    print(111)
    print(p.readlines())
```

```python
import subprocess
res = subprocess.run([ "sleep 1 &&cxz"],shell=True,stdout=subprocess.PIPE, stderr=subprocess.STDOUT)
print(res.returncode)
print(str(res.stdout))
print(res.stderr)
```

```python
import os

print(os.environ['HOME'])
print(os.path.expandvars('$HOME'))
print(os.path.expanduser('~'))
```

```python

```