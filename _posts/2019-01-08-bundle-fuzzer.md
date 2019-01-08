---
layout: post
title:  "How to Bundle Fuzz"
date:   2019-01-08
author: Dr. Nielbo
#permalink: blog/build-a-website.html
---

# How 2 Bundle Fuzz with Fuzz Bundler #

1. catch the fuzz
2. bundle it

or

```py
from fuzzbundler import bundle

OUT = list()
for item in fuzz:
  OUT.append(bundle(item))
```
