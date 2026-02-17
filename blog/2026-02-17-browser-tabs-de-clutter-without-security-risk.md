---
slug: browser-tabs-de-clutter-without-security-risk
title: Browser Tabs De Clutter without security risk
authors:
  - michal
tags:
  - productivity
  - open_source
  - coding
---
Recently, I joined a new company as a Senior Engineer. I am super excited as it’s only the third company I’ve worked for in 15 years in IT, but I also came back to work after almost 3 years of a career break.

I received my company laptop and started onboarding process. What I see next? 

Don't know how, don't know when I have around 60-70 tabs open, some websites opened multiple times, causing my head burn with cognitive overload when deciding which ones were truly important. 

The next day, not only were the same tabs waiting for me, but I also opened even more tabs relevant to the task at hand.

Of course, I could add them to the reading list, but knowing myself, the list would grow ad infinitum and I'd never opened them again. 

I could add all of them to bookmarks for follow-up later, but then I'd need to manually deduplicate them, select all of them, create new folders, and name them. Too much hassle for such a simple task.

Maybe a plugin could help? I researched a few, but either they didn’t have the functionality working the way I wanted or had bad reviews. And honestly, in the AI era where code is cheap and many malicious actors can pass through the [Chrome Web Store review](https://layerxsecurity.com/blog/aiframe-fake-ai-assistant-extensions-targeting-260000-chrome-users-via-injected-iframes/) or even get [Google’s “Featured” badge](https://www.ox.security/blog/malicious-chrome-extensions-steal-chatgpt-deepseek-conversations/), do I really want to risk installing third-party software?

This is how my first open-source contribution was born: **Tabs de Clutter**. I implemented a plugin for Chrome and Firefox that allows tab deduplication and bookmarking in dated folders for follow-up later. I even added configuration for bookmark folder naming, new folder creation or folder name iteration.

I've already submitted it to the Firefox Add-on Hub as there are limitations to install it manually. You can find installation instructions and verify the source code yourself [here](https://github.com/micjez/tabs_de_clutter). I'm happy to hear your opinions or suggestions on what I can improve.

For me, it just works. With one click, I bookmark all the tabs and create a reading list related to the topic I'm interested in at the moment. I feel so much relief when I have zero tabs open every morning.