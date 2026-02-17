---
layout: post
title: "AI Revisited: How It's Changed My Work"
categories: Technology
excerpt: Three years after writing about my uncertainties with AI, here's how daily use as a principal developer on TidyCal has shaped my perspective.
published: false
---

Almost three years ago I wrote [Some Thoughts on AI](/blog/2023/some-thoughts-on-ai/) wondering how AI would change our work and our lives. I was curious, a little cautious, and genuinely unsure how things would play out. A lot has happened since then, and my perspective has shifted considerably. Not from reading about AI, but from using it every day as a principal developer on TidyCal.

## What I've Learned Since Then

When I first started using AI for programming at work I wasn't completely sold on it. The early models would write code that was close, but myopic. They'd miss much of the nuance of the problem they were trying to solve. I'd get a wall of code back, but because I couldn't fully trust it I still felt the need to read every line. It often took more time for me to understand what it wrote and spot the issues than it would have taken to just write it myself. I should have known that would be short lived, but at the time AI was being pushed so hard and I didn't really get why.

Now, particularly with Claude Code, I can lean on AI to write most things without me reading every single line. But it's more nuanced than I originally imagined. It's not just "ask and approve." My time has shifted from writing code to having deep conversations about what needs to happen, making sure we're aligned on the requirements and edge cases before any code gets written. The gaps that come up are usually things I overlooked when defining the specs, not things the AI got wrong on its own. It's genuinely collaborative.

One of my biggest takeaways is that the skills which matter most now are communication skills. The more effectively you can communicate with AI the better the results. Knowing what to ask, how to scope a problem, and when to push back on AI output all matter. Your performance is still largely tied to your ability to do those things well, and your desire to produce high quality results.

And calling AI "just a tool" doesn't quite capture it anymore. A tool implies something that makes a particular task easier, but this is more than that. It's not just changing what's displayed on our screens. It's powering actual world-changing applications like autonomous vehicles, expanding access to healthcare, and certainly much more than we can even estimate right now. It feels less like a tool and more like a new part of our world has been unlocked: an amazingly accessible portal to the combination of all our knowledge, history, and creations, with the ability to build and improve on everything we've already accomplished.

## AI as a Force Multiplier on TidyCal

[TidyCal](https://tidycal.com) is AppSumo's scheduling tool, and I'm a principal developer. Here's where AI, specifically Claude and Claude Code, has made a tangible difference in my work.

**Speed and quality**

Projects that took our small team a month before now take just a few days. New features that used to require days of scaffolding and wiring things up can be prototyped in an afternoon, which means we spend more of our time refining the product and less on the groundwork. Gone are the days of lingering bugs that were difficult to reproduce and pin down. AI can often spot the source of a bug in less than a minute and offer a fix in about the same amount of time. Not only is this a productivity booster, but a learning experience if you take the time to understand what actually went wrong and how it's being fixed.

**Code review and the new bottleneck**

It's now possible to create an endless stream of PRs based on customer requests, bugs, internal ideas, you name it, that are "ready" to merge. AI has made the creation side almost trivially fast. But that shifts the bottleneck to the review process: are these changes objectively good to add? Do they actually solve the problem? Is the code sound? Does it follow existing conventions and patterns?

Code review is still a hands-on process for our team, but the nature of it has changed. A lot of it now consists of having a conversation with Claude about what's broken, what can be improved, and then landing on the most important items to address. We delegate much of our GitHub interactions to Claude, but we're still the ones behind the comments and the decisions. That feels important. Human oversight rather than letting an agent run unsupervised. Without that, you risk building up layers and layers of issues that compound over time. The team's expertise and institutional knowledge are what keep the resulting work from becoming a purely vibe-coded product.

## What It Means to Be a Dev in the AI Era

> AI amplifies judgment. It doesn't replace it.

Knowing the codebase, understanding the business context, and having years of experience with the domain all matter more now, not less. AI can generate code fast, but someone still needs to know whether that code is right for the system it's going into.

Anyone can ask AI to open PRs with code changes, and that's awesome. But having someone with a strong technical background review those changes before they ship is still an important part of the process. In fact, we already do this on my team at AppSumo. People in non-engineering roles contribute code with the help of AI, and current developers shift into more of an inspector role, making sure everything is up to code. (Pun intended.)

More broadly, I think humans are just as important now as they ever were. We can just do things better and more efficiently. That may mean roles will shift, but people aren't likely going to be interested in using software or services that aren't at least supported by humans. In the end we're building these tools, including AI, for the betterment of ourselves, not to run us off the planet.

## Where I Draw the Line

AI is showing up outside of work too. Here in San Francisco we regularly use Waymo, and honestly the AI "driver" is safer than most human drivers. I'm all for it. But not everything translates so cleanly.

As a music lover and musician, I'll say that AI-generated art gives me pause. I often listen to lo-fi jazz while I work, and I value the fact that it's created by real musicians. At some point I realized a channel I'd been listening to was fully AI-generated, and it made me start checking every channel to make sure the music was made by real people.

Art is performative and expressive. I don't think you can truly create art by prompting an AI to do it for you. It's not unlike commissioning a painting.

> If you describe what you want and someone else paints it, are you the artist or are they?

What makes this interesting is the contrast with programming. You could argue that AI enabling more people to write software is a similar dynamic, but I actually think that's a great thing. Programming is fundamentally functional. A binary tree search serves a singular purpose without carrying any emotion or human inspiration. The bar to learn programming has been relatively high for most people because it's highly technical and, honestly, often boring unless you're genuinely interested in it. Lowering that bar feels like a clear win.

Music and visual art are different. They carry emotion, intention, and the weight of the effort behind them. I can't imagine wanting to go to a museum to view AI-generated art or a concert to hear AI-generated music. If real musicians were performing AI-written songs, I could appreciate the performance itself. That's its own art. But I don't think I'd have the same admiration for the compositions. There's something about knowing a human poured themselves into creating something that makes it resonate differently.

## Looking Ahead

I'm not an economist and don't feel qualified to make sweeping predictions about how AI will affect society as a whole. But I'm optimistic that we'll see far-reaching net benefits, even with some growing pains along the way. I believe the motivation to learn will always exist because innate human curiosity is how we got here in the first place. AI feels like a conversational way to interact with the internet and all the documented knowledge up until this point. So while it can be an easy way to cut corners, it's also an incredible way to learn.

I'm still curious about how AI will continue to transform our lives and what will be gained and lost in the process. That hasn't changed. What has changed is that I'm no longer just wondering from the sidelines. I'm shipping features with it every day on TidyCal, and my perspective is shaped by that experience now, not speculation.
