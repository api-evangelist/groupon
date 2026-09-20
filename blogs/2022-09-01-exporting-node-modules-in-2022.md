---
title: "Exporting Node Modules in 2022"
url: "https://medium.com/groupon-eng/exporting-node-modules-in-2022-e8fd97f0f5a9?source=rss----5c13a88f9872---4"
date: "2022-09-01"
author: "David Bushong"
feed_url: "https://medium.com/feed/groupon-eng"
---
Groupon maintains literally hundreds of NPM modules, both open source and internal. Many of these are consumed by our custom NodeJS-based middleware web layer we call “The Interaction Tier” (itself a topic for another post someday). As folks write new modules, a common question is “what’s the best way to export things from our published modules to maximize compatibility?” — and that is the topic of this post.
