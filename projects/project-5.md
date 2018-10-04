---
layout: project
type: project
image: images/cpp.png
title: 3. Database Engine Implementation
permalink: projects/dbi
# All dates must be YYYY-MM-DD format!
date: 2018-04-01
labels:
  - C++
  - Multithreading (pthreads)
  - mutex
  - lex
  - yacc
  - Valgrind
  - gdb
summary: An efficient and memory optimal relational database engine built from ground up
---
<img class="ui image" src="../images/cpp.png">

## Summary
* A relational Database Engine/System Implementation built from ground up in C++. 
* Supports a subset range of complex SQL querries in valid SQL syntax
* Has memory optimal and multithreaded implementations of all relational operations such as Joins, Group-By, Distinct, Order BY, Select, Project, etc.
* Has Concurrent Pipe implementations to help with data flow throughout and between operations
* Supports Query Optimisation on the basis of relational data and query planning (structuring) 
* Benchmarked the database with TPCH data for tables/relations of size of 1GB

Project [Github repository link](https://github.com/mlzepplin/DBI)

