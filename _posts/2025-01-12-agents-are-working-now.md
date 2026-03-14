---
title: Agents are working now
author: Sarthak Tiwari
date: 2025-01-12 22:00:00 +0530
categories: [Engineering, ]
tags: [Engineering, AI]
pin: false
published: true
---

About a year ago I wrote about the orchestration layer being the interesting problem. It still is, but something has shifted.

The agents I was building in early 2024 were brittle. They'd hallucinate tool arguments, lose track of goals mid-task, require too much hand-holding to be useful. Interesting as experiments, not useful as tools.

The same patterns are working now. Built a small agent last month that takes a GitHub issue, explores the relevant code, and produces a patch with context. It's not magic - it gets things wrong, needs review - but the failure modes are predictable enough that it's actually useful. That's the shift.

The infrastructure around agents has matured. Better function calling, better context management, evals that measure the right things. The hard problems aren't solved but they're mapped. You know what you're solving for.

Curious where this goes in the next year.
