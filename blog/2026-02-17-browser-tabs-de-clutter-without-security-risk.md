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

The next day, not only were the same tabs waiting for me, but I also opened even more tabs relevant to the task at hand. And it's a huge mental baggage for me knowing that one day I should read them all. The same happens for me with unread emails, todo tasks or flaky tests.

That's why I've built **System0** - each week I spend time on clean up: 
- archive or delete unread emails
- prioritize, delete or move tasks to indefinite future task list
- fix or delete flaky tests. 
 
But what to do with those dozens of tabs?

Of course, I could add them to the reading list, but knowing myself, the list would grow ad infinitum and I'd never opened them again. 

I could add all of them to bookmarks for follow-up later, but then I'd need to manually deduplicate them, select all of them, create new folders, and name them. Too much hassle for such a simple task.

Maybe I could find and install a browser plugin that could help me with maintenance? 

I researched a few, but either they didn’t have the functionality working the way I wanted or had bad reviews. And honestly, in the AI era where code is cheap and many malicious actors can pass through the [Chrome Web Store review](https://layerxsecurity.com/blog/aiframe-fake-ai-assistant-extensions-targeting-260000-chrome-users-via-injected-iframes/) or even get [Google’s “Featured” badge](https://www.ox.security/blog/malicious-chrome-extensions-steal-chatgpt-deepseek-conversations/), do I really want to risk installing third-party software? Whom I can trust with my data?

This is how my first open-source contribution was born: **Tabs de Clutter**. I implemented a plugin for Chrome and Firefox that allows tab deduplication and bookmarking in dated folders for follow-up later. I even added configuration for bookmark folder naming, new folder creation or folder name iteration.

You can find installation instructions and verify the source code yourself or with AI [here](https://github.com/micjez/tabs_de_clutter). In Chrome you can install package yourself in development mode, but in Firefox, it's not possible, so you might add extension from [Add-On Store](https://addons.mozilla.org/en-US/firefox/addon/tabs-de-clutter/). 

I'm happy to hear your opinions or suggestions on what I can improve.

For me, it just works. With one click, I bookmark all the tabs and create a reading list related to the topic I’m interested in at the moment. I feel so much relief knowing that every morning I can start my day fresh, without a long waiting queue of unfinished work.