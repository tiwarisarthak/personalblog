---
title: The orchestration layer is the interesting problem
author: Sarthak Tiwari
date: 2024-03-10 22:30:00 +0530
categories: [Engineering, ]
tags: [Engineering, AI]
pin: false
published: true
---

Been spending evenings this past month building small things with LLMs. Most of the discourse is about which model is best, which benchmark, which context window. That's fine but it's not the interesting part.

The interesting part is orchestration. How do you get an LLM to reliably use tools? How do you chain calls without context getting corrupted halfway through? How do you handle the case where the model hallucinates a tool argument and your system needs to recover gracefully? These are hard problems that don't have clean answers yet.

LangChain has a lot of abstractions but at the end of the day it's all glue code. The primitives are still being figured out. Which means the space is genuinely open.

I've worked on workflow orchestration before. The same fundamental questions come up: state management, failure recovery, observability, idempotency. The domain is new but the engineering problems are familiar. That's what makes it exciting.

Going to keep hacking on this. Something useful will fall out eventually.
