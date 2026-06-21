---
title: "Building at the Speed of Thought: AI as a Force Multiplier"
date: 2025-12-31
draft: false
tags: ["Engineering", "AI", "Efficiency", "Meta"]
summary: "How I built this blog from 'empty folder' to 'production' in under an hour using AI."
---

I am a builder at heart. Setting up personal websites was historically a chore.

It meant weekends of friction: fighting CSS, debugging obscure build errors and wrestling DNS propagation. It was "undifferentiated heavy lifting" (work that had to be done but added zero unique value).

This time I tried something different. I built this site (`tribhuwan.dev`) not just *with* AI but *through* AI. Entire processes (from empty directories to live global SSL) took less than an hour.

### The Surprise Factor
Surprise wasn't that AI could write code. We know it can do that.
Surprise was continuity of flow.

When you hit snags (like version mismatches in CI/CD pipelines or canonicalization issues with DNS) you normally stop. You Google. You read StackOverflow. Momentum dies.

I simply stated intent: *"I need a deployment script for Hugo on GitHub Pages."*
When errors popped up I didn't debug manually. I fed context back to AI. It corrected syntax, adjusted version numbers and we moved on.

Friction didn't disappear but it became negligible. It felt less like coding and more like directing.

### The Stack (Crisp & Clean)
For those curious about architecture we kept it ruthlessly simple to ensure performance and longevity:

* **Engine:** **Hugo** (Static Site Generator). No databases, no security vulnerabilities, blazing fast.
* **Skin:** **PaperMod**. Minimalist themes respect reader time.
* **Pipeline:** **GitHub Actions**. Simple YAML workflows build and deploy automatically on every push.
* **Edge:** **Cloudflare**. Handles DNS, SSL and redirects before traffic hits servers.

### Lessons for Leaders
I am sharing this process to highlight shifts in how we work.

Engineers often take pride in doing things the hard way. We treat struggle as badges of honor. As leaders our job is maximizing impact and guiding teams toward efficiency.

AI didn't do work *for* me. It removed drag *from* me. It handled boilerplate and config syntax allowing me to focus entirely on architecture and messaging.

If you are holding back on building something because you dread setup: **start now.** Barriers to entry have never been lower.