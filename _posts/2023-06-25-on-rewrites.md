---
title: On Rewrites
author: Sarthak Tiwari
date: 2023-06-25 22:00:00 +0530
categories: [Engineering, ]
tags: [Engineering]
pin: false
published: true
---

Every developer has a rewrite they want to do. A system that grew organically and is now a mess. Edge cases bolted on over years. A module that works but that nobody wants to touch.

The argument for a rewrite is always compelling at the start. Clean slate. Right abstractions this time. Modern tooling. Everyone excited.

Then three months in you're rebuilding the same edge cases, except now they're harder because the original author who understood them left six months ago. And halfway through you realize the "mess" in the old system was load-bearing. It was handling a dozen things your beautiful new design hasn't thought about yet.

I'm not saying never rewrite. Sometimes the old system really is past saving. But the bar for a full rewrite should be much higher than "I don't like how this looks". Incremental is almost always better. Boring, unsexy, but better.
