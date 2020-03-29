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
![Bacteria Code](/img/mit-program-bacteria_0.jpg "MIT Program Bacteria ")

```python
from Bio import Seq10

for seq_record in Seq10.parse("ls_orchid.gbk", "genbank"):
    print(seq_record.id)
    print(repr(seq_record.seq))
    print(len(seq_record.id))
    
    
Z78533.1
Seq('CGTAACAAGGTTTCCGTAGGTGAACCTGCGGAAGGATCATTGATGAGACCGTGG...CGC', IUPACAmbiguousDNA())
740
...
Z78439.1
Seq('CATTGTTGAGATCACATAATAATTGATCGAGTTAATCTGGAGGATCTGTTTACT...GCC', IUPACAmbiguousDNA())
592


 
```

Sarah is a biology major, this semester she's encountering biological computing for the first time this semester.

She's never written a line of `code` before, of course she's heard of python, java, docker, cloud computers, oh even the good old compilers.