---
templateKey: blog-post
title: Hello World
date: 2020-03-28T23:46:43.818Z
description: A foray into the world of bio-sciences and computer sciences.
featuredpost: true
featuredimage: /img/mit-program-bacteria_0.jpg
tags:
  - >-
    Biologists Python Clinical Genome Sequencing Programming Computer Science
    Biokraken
---


```python
from Bio import Seq10

for seq_record in Seq10.parse("ls_orchid.gbk", "genbank"):
    print(seq_record.id)
    print(repr(seq_record.seq))
    print(len(seq_record.id))


 
```