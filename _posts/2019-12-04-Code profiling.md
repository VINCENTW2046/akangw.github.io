---
layout: post
title:  Code Profiling
date:   2019-12-04 12:00:00
description:
---


You can follow the procedures and do code profiling:
* Use valgrind to generate a file "callgrind.out.x" where x is some number 
   * requirement: valgrind
   * ```valgrind --tool=callgrind [call your code with arguments]```
* Use the pythyon code <a href="https://github.com/jrfonseca/gprof2dot" target="_blank">gprof2dot.py</a> 
   * requirement: python, graphviz
   * ```python gprof2dot.py -s -f callgrind ./callgrind.out.x | dot -Tpdf -o output.pdf```