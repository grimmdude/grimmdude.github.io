---
layout: post
title: "AI Revisited: How It's Changed My Work"
categories: Technology
excerpt: Three years after writing about my uncertainties with AI, here's how daily use as a principal developer on TidyCal has shaped my perspective.
published: true
---

Almost three years ago I wrote [Some Thoughts on AI](/blog/2023/some-thoughts-on-ai/) reflecting on how AI might change our work and our lives. At the time, I was curious but mostly cautious and unsure of how it would all play out. 

Since then, a lot has changed, including my perspective. As the principal developer for AppSumo Originals, AI has become a core part of my team’s daily workflow, especially on [TidyCal](https://tidycal.com), AppSumo’s scheduling tool.

## From Skepticism to Daily Use

The early models would write code that was close, but myopic. They'd miss much of the nuance of the problem they were trying to solve. I'd get a wall of code back that I couldn't fully trust and had to read through line by line to catch the issues, taking me more time than if I had just written the code myself. I should have known that would be short-lived, but in the moment the frustration left me confused as to why AI was being pushed so hard.

Fast forward to today, particularly with Claude Code, I can lean on AI to write most things without me reading every single line. It's developed the nuance that it so desperately lacked; it's not just "ask and approve." My time has shifted from writing code to having thoughtful conversations about what needs to happen, making sure we're aligned on the requirements and edge cases before any code gets written. The gaps that come up are usually things I overlooked when defining the specs, not things the AI got wrong on its own. The entire process is much more collaborative. 

## AI as a Force Multiplier on TidyCal

Here's where it's made a tangible difference.

**Speed and quality**

Projects that took our small team a month before now take just a few days. New features that used to require days of scaffolding and wiring things up can be prototyped in an afternoon, which means we spend more of our time refining the product and less on the groundwork. Gone are the days of lingering bugs that were difficult to reproduce and pin down. AI can often spot the source of a bug in less than a minute and offer a fix in about the same amount of time. Not only is this a productivity booster, but also a learning experience if you take the time to understand what actually went wrong and how it's being fixed.

**Code review and the new bottleneck**

It's now possible to create an endless stream of PRs based on customer requests, bugs, internal ideas... you name it, that are "ready" to merge. AI has made the creation side almost trivially fast. But that shifts the bottleneck to the review process: are these changes objectively good to add? Do they actually solve the problem? Is the code sound? Does it follow existing conventions and patterns?

Code review is still a hands-on process for our team, but the nature of it has changed. A lot of it now consists of having a conversation with Claude about what's broken, what can be improved, and then landing on the most important items to address. We delegate much of our GitHub interactions to Claude, but we're still the ones behind the comments and the decisions. That feels important. Human oversight rather than letting an agent run unsupervised. Without that, you risk building up layers and layers of issues that compound over time. The team's expertise and institutional knowledge are what keep the resulting work from becoming a purely vibe-coded product.

**Non-engineers contributing code**

Anyone can ask AI to open PRs with code changes, and that's awesome. In fact, we already do this on the AppSumo Originals team. People in non-engineering roles contribute code with the help of AI, and current developers shift into more of an inspector role, making sure everything is up to code. (Pun intended.) Having someone with a strong technical background review those changes before they ship is still an important part of the process.

## What I've Taken Away

One of my biggest takeaways is that the skills which matter most now are communication skills. The more effectively you can communicate with AI, the better the results. Knowing what to ask, how to scope a problem, and when to push back on AI output all matter. Your performance is still largely tied to your ability to do those things well, and your desire to produce high-quality results.

> AI amplifies judgment. It doesn't replace it.

Knowing the codebase, understanding the business context, and having years of experience with the domain all matter more now, not less. AI can generate code fast, but someone still needs to know whether that code is right for the system it's going into.
