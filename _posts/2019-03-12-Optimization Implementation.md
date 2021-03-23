---
layout: post
title:  Optimization Implementation
date:   2019-03-12 12:00:00
description: 
---

#### CPLEX
<ul>
    <li><a href="https://my15.digitalexperience.ibm.com/b73a5759-c6a6-4033-ab6b-d9d4f9a6d65b/dxsites/151914d1-03d2-48fe-97d9-d21166848e65/home" target="_blank">Download CPLEX via your academic account</a></li>
    <li><a href="https://www.ibm.com/support/knowledgecenter/en/SSSA5P_12.10.0/ilog.odms.studio.help/Optimization_Studio/topics/COS_installing.html" target="_blank">Installation</a></li>
	<li><a href="https://www.ibm.com/support/knowledgecenter/SSSA5P_12.10.0/ilog.odms.cplex.help/CPLEX/GettingStarted/topics/set_up/GNU_Linux.html" target="_blank">Set up CPLEX</a></li>
	<li><a href="https://www.ibm.com/support/knowledgecenter/SSSA5P_12.10.0/ilog.odms.cplex.help/refcallablelibrary/homepageCrefman.html" target="_blank">Documentation</a></li>
</ul>



#### Gurobi
<ul>
    <li><a href="http://abelsiqueira.github.io/blog/installing-gurobi-7-on-linux/" target="_blank">Installation</a></li>
    <li><a href="https://www.gurobi.com/documentation/" target="_blank">Documentation</a></li>
</ul>



#### CVX
<ul>
    <li><a href="http://cvxr.com/cvx/doc/intro.html" target="_blank">Tutorial</a></li>
</ul>

#### NEOS
<ul>
    <li><a href="https://neos-server.org/neos/" target="_blank">NEOS Server</a></li>
</ul>

#### Benchmarks for Optimization Software
<ul>
    <li><a href="http://plato.asu.edu/bench.html" target="_blank">Hans D. Mittlemann</a></li>
</ul>


#### Coding Languages
<ul>
    <li><a href="http://www.cplusplus.com/" target="_blank">C++</a></li>
    <li><a href="https://python.org/" target="_blank">Python</a></li>
    <li><a href="https://julialang.org/" target="_blank">Julia</a></li>
</ul>


#### Coding Style
<ul>
    <li><a href="http://google.github.io/styleguide/" target="_blank">Google Style Guides</a></li>
</ul>

#### Code profiling
* Use valgrind to generate a file "callgrind.out.x" where x is some number 
   * requirement: valgrind
   * ```valgrind --tool=callgrind [call your code with arguments]```
* Use the pythyon code <a href="https://github.com/jrfonseca/gprof2dot" target="_blank">gprof2dot.py</a> 
   * requirement: python, graphviz
   * ```python gprof2dot.py -s -f callgrind ./callgrind.out.x | dot -Tpdf -o output.pdf```



#### Parallel computing
<ul>
    <li><a href="https://computing.llnl.gov/tutorials/parallel_comp/" target="_blank">Introduction to Parallel Computing</a></li>
    <li><a href="https://www.openmp.org/resources/tutorials-articles/" target="_blank">OpenMP Tutorials</a></li>
    <li><a href="https://computing.llnl.gov/tutorials/openMP/" target="_blank">OpenMP</a></li>
</ul>


If you want to compare CPUs, the following link might be helpful.

<ul>
    <li><a href="https://www.cpubenchmark.net/singleThread.html" target="_blank">CPU Benchmarks</a></li>
</ul>