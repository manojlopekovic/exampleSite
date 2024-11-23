---
title: "Python Web Development with FastAPI"
date: 2024-11-23T14:35:08+01:00
draft: true
ShowToc: true
tags: ["python", "web", "fastapi"]
categories: ["tech", "tutorials"]
keywords: ["web development", "python backend", "api"]
hideSummary: true
---

FastAPI is a modern Python framework for building APIs...

We'll build a simple API that can:
- Handle HTTP requests
- Connect to a database
- Run in a Docker container

```goat
      .               .                .               .--- 1          .-- 1     / 1
     / \              |                |           .---+            .-+         +
    /   \         .---+---.         .--+--.        |   '--- 2      |   '-- 2   / \ 2
   +     +        |       |        |       |    ---+            ---+          +
  / \   / \     .-+-.   .-+-.     .+.     .+.      |   .--- 3      |   .-- 3   \ / 3
 /   \ /   \    |   |   |   |    |   |   |   |     '---+            '-+         +
 1   2 3   4    1   2   3   4    1   2   3   4         '--- 4          '-- 4     \ 4

```