---
title: "Tiger Compiler"
description: "Compiler for the toy language Tiger writen in C++"
tags: ["project"]

slug: project

cascade:
  showDate: false
  showAuthor: false
  invertPagination: true
---

## Tiger Compiler is a third year project that consists of the creation of a compiler for the Tiger toy language.
Based on Andrew Appel's [Modern Compiler Implementation in ML](https://www.cs.princeton.edu/~appel/modern/ml/), this project, in groupe of 4, aims to make learn the theory of compilation via an implementation in C++. This is the biggest project of the third year, spanning on a total of 14 weeks.

The project was divided in 3 part:
- The frontend: Where the lexing, parsing of the grammar, binding and type-checking was done. Everything was based on the Visitor design patern.
- The middle-end: Where an optionnal step, TC-L, in which we use the LLVM library as a backend, was available. Also, the transformation into intermediate representation, first of high level, then of low level, is carried out.
- The backend: Where we emit the machine code ([MIPS](https://en.wikipedia.org/wiki/MIPS_architecture)), first with an infinite number of registers available before a register allocation step, then with a realiste register number after a basic register allocation step on graph colorization.

The repository on which the project is hosted is private, on request of the assistants.

If you want to learn more about this project, I strongly recommend to take a look at the [Assignments page](https://assignments.assistants.epita.fr/index.html).