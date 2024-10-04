---
title: "42sh"
description: "Posix shell recreation in C"
tags: ["project"]

slug: project

cascade:
  showDate: false
  showAuthor: false
  invertPagination: true
---

## 42sh is a third year project that consists of creating a fully functional C-based POSIX Shell from scratch. 
The project is run by a team of 4 over a period of 1 month.

In this project, I was in charge of multiples things:
- The build system: autotools.
- The testsuite: Fully written in python, it compares the project binary with bash (stdout, stderr and return value).
- The GitHub: Maintainer of the repository on Github (The repo is private on request of the assistants). 
- CI/CD: A basic CI/CD that started the testsuite and checked the coding-style at each push and MR.
- Some various 42sh features: the unset and export builtin, the variable and the IO backend.

If you want to learn more about the project, I suggest to take a look at the [Assistants's trove](https://trove.assistants.epita.fr/).