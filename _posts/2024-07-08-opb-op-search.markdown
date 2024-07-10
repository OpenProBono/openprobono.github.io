---
layout: post
title: "Introducing the OpenProBono Opinion Search tool"
date: 2024-07-08 12:09:45 -0400
---

We are hard at work building and evaluating our AI, getting it ready to be released to the public here at OpenProBono. However, we found that one of the ‘tools’ we built for our AI to interact with the Courtlistener API could be useful even on its own. So we decided to do just that and release it before our actual full legal AI chatbot that we are working towards.

The tool uses the Courlistener API to search for case opinions, it summarises and embeds it into a vector DB any opinions that it hasn’t seen before. It then searches its database and returns the relevant opinions and the specific matching sections of the opinion text to your query. The tool also has a keyword search, so you can find snippets containing exact words or phrases you want to include, along with date and jurisdiction filters. If you are interested in more technical details, we have the full product code (along with our progress on the end product legal AI) up on GitHub. We welcome anyone reproducing it or making improvements and we will have some more technical blog posts in the future.

We are not the only ones to do this! The tools descrybe.ai and olaw both also allow you to easily search the Courtlistener API using AI, and you should check both of them out too!

Lastly, if you are interested in keeping up with us and being one of the first to try out our full-fledged legal AI, fill out this interest form.