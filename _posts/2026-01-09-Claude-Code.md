---
layout: post
title: "Claude Code: Next-Level Vibe Coding"
published: true
---

![From the ancients to AI](../images/claude-code-bfih-screenshot.png)

*The BFIH web app created in less than a day with Claude Code.*

---
I've tried a number of AI-assisted coding environments (IDE's) and strategies: from Cursor, to Manus, to Perplexity.AI "Labs" mode, to Google AI Studio "Build" mode, etc.  All have impressed me up to a point. But all have failed me once I got past that initial phase of creating the UI for an app and got down to digging into making it work.  These AI coding systems tend to eat their own tail as they revise the revised and revise the stuff that you're satisfied with and don't want touched. And they never really get down to being able to accurately code up the core backend capability at the heart of an interesting app.

That is, until now with the latest release of Anthropic's Claude Code.  Though not perfect, this multi-agent AI coding system is the best I've used. I truly think it signals a step-change in automatic coding capability that we've just not had before. 

I applied it in about a day's worth of coding to "build an educational game app about the Bayesian Framework for Intellectual Honesty (BFIH)".  The result is the **_"BFIH Tournament" web app_**, an app built by me "talking" to Claude Code. [^ftnote] It's the first app I've built where I didn't alter any of the code manually -- I even told Claude Code what the core algorithms should do and let it auto-iterate until they worked properly.  

The BFIH Tournament app accepts a topic from the user, performs a thorough BFIH analysis using OpenAI's GPT-5.2 to do the heavy lifting, and presents the results incrementally to the user in a compelling visualization-packed UI/UX.  The results unfold sequentially from the perspectives ("paradigms") used to analyze it, the hypotheses generated, and the priors assigned based upon each perspective. At this point, the human player then places bets on which hypotheses will have the highest posterior probability. The app then proceeds to reveal the player's payoff under each perspective.

It's pretty cool!  The human player gets to see how closely their views align with a maximally intellectually honest view and with other views that have different realistically reasonable biases.  My original intent was to make it a multi-player, multi-round tournament, hence the name. For now, it's a single-player "game", and only a game in the sense that you can bet and it displays payoffs but there's no accumulation of points and summary winning or losing -- i.e., not really a game.  Interesting nonetheless.

By now, there are a bunch of raves about the latest release of Claude Code on the internet. And, I wanted to see what a BFIH analysis might turn up in terms of more substantial assessment of Claude Code relative to the current competition. I ran this topic through my new Claude Code-built web app to find out. And so, here's the first BFIH analysis I'm posting that was generated automatically without my interaction other than inputting the topic to investigate.  

I still used Perplexity.AI to write the blog post below after feeding it the analysis report from the web-app written by Claude Code. 

---

**The research topic:**

> **_"Claude Code, as of January 2026, has revolutionized AI-powered 'vibe coding'."_**

**The upshot:** Yes, for some applications, but we need more time for the latest version to be used more broadly and analyzed more deeply -- most of the analysis was about vibe coding in general and earlier releases of Claude Code, so this latest version hasn't yet been fully digested.

---

Below is the plain-language synopsis of the BFIH findings, which includes a link to the full BFIH analysis report with bibliography.

<div align="center">⁂</div>

{% include claude-code-include.md %}

---

Thank you for your time and mindshare,

-Michael L. Thompson ([LinkedIn profile](https://www.linkedin.com/in/mlthomps))

<div align="center">⁂</div>

[^ftnote]: I hope to deploy the BFIH Tournament web app to Google Cloud Services shortly, at which time I'll update this post with the link.

