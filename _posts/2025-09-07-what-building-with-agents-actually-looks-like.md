---
title: What building with agents actually looks like
author: Sarthak Tiwari
date: 2025-09-07 22:00:00 +0530
categories: [Engineering, ]
tags: [Engineering, AI]
pin: false
published: true
---

Eight months since my last post on this. Some things learned from actually building with agents:

The reliability problem is more tractable than I expected if you scope tasks tightly. Agents fail on vague instructions for the same reason junior engineers fail on vague instructions. Specificity helps a lot.

The observability story is still weak. When an agent makes ten tool calls to complete a task, understanding why it took the path it did is hard. Logging helps but you're still mostly pattern-matching on behavior rather than reasoning about it. Need better tooling here.

The cost question is real now. These systems are not free to run. The cost-per-task math changes what's worth automating. Tasks that were obvious candidates at "nearly free" look different at actual cost.

None of this is discouraging. It's just engineering. The problems have answers.
