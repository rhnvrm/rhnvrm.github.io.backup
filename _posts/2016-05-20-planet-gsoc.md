---
layout: post
title: Building Planet GSoC
tags:
- gsoc
---

There were many emails in the GSoC mailing list regarding 'sharing' blogs
with the GSoC community. Many GSoC students keep blogs to track their
progress. It becomes really tough to track hundreds of blogs so I thought
of starting a blog aggregator. 

Most of the solutions that had been developed until now required setting up a server
that would generate a static file of all the blogs. But I wanted a solution
that was easy to set up and could be deployed by anyone by clicking a single button on github.
The motivation for this was my conversation with James Lopeman (meflin) on irc who
is an org-admin at the Python Software Foundation. Before
that conversation, I had already set up a simple method using [river5](https://github.com/scripting/river5)
developed by
[Dave Winer](https://github.com/scripting) but later I extended it to include a deploy on openshift button. 

Currently, around 48 blogs are indexed by [PlanetGSoC](http://planetGSoC.github.io). It 
can be forked by anyone to deploy their own planet on GitHub.io since it uses 
JSONP requests to fetch the JSON river from the server running on openshift. 

Feel free to fork the project or contribute! And if you have a blog related to GSoC be 
sure to send a pull request.
