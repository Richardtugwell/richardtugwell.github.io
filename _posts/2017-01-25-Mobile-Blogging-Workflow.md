---
layout: post
title: Mobile Blogging Workflow
date: 2017-01-25 14:34
---
When I last played with blogging about 10 years ago, mobile wasn't really an option, and I eventually got fed up with the bloated inconvenient packages like Blogger and Wordpress. In the last few years this has changed completely though, so I'm giving it another try.

Here's a brief overview of the workflow and technologies I've adopted. I'm doing all this on a 9.7" iPad Pro with the smart keyboard. More about this later.

Here's a run down of the technologies involved.

# Publishing

**Jekyll** - static website generator. Not especially a mobile option, but static sites are the way to go for fast responsive sites and that's aimed at mobile consumers. In addition clean coding with Markdown and the DB / platform agnosticism appeal to the geek in me.

**Github Pages** - There are many ways to host a static website pretty much for nothing. I've picked Github Pages for the ease of deployment and because I'm already a Github user.

**Amazon S3** - For storing web accessible assets such as files and images.

**Dropshare** - An app for uploading assets from iOS to S3

**Disqus** - For static websites you need a third party solution for things like comments. Disqus is the market leader here. I may write my own simple solution at some future point.

# Editing

**Editorial** - A lightweight markdown editor with Github integration

**Working Copy** - A Git client for the iPad. This lets me manage version control on the iPad and commit/push to Github when ready. It means I can also easily synchronise the code if I've updated the blog pages from somewhere else.

# Images