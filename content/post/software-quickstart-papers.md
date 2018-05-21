+++
title = "Software Systems Papers"
date = 2018-04-28T17:37:38-07:00
draft = true

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []
categories = []
summary = "Software Engineering Quick Start Guide"
# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
# Use `caption` to display an image caption.
#   Markdown linking is allowed, e.g. `caption = "[Image credit](http://example.org)"`.
# Set `preview` to `false` to disable the thumbnail in listings.
[header]
image = ""
caption = ""
preview = false
+++

A few of my friends have been looking for papers to "get into" computers. They were coming from a non-technical background and didn't want to get lost in technical jargon.

These are a few of papers that helped me the most when I was trying to understand "what is a computer" and "what they can and cannot do". Understanding the philosophy in the minds of the engineers who designed these systems contextualizes how the systems were built and their limitations.

## Worse is Better
This philosophy serves as the backbone for software engineering. It’s more of a high level discussion than a technical paper per se but gets you into the software mindset. Every software engineer I've met knows this philosophy. It's less important to fight over the details in the story and to instead look for the moral of the story.
http://www.mit.edu/~6.033/papers/Worse_is_Better.pdf


## Unix Time-Sharing System
Understanding UNIX is to understand computers. Most computers are unix based, and practically all servers are.  This is moderately technical, but almost completely abstracts away the complexity of the actual CPU underneath it.
https://people.eecs.berkeley.edu/~brewer/cs262/unix.pdf

## Domain Name Service
Within computers, there are lot of lessons to learn, but to fast forward to DNS (Domain Name Service) would help clarify the enigma that is the world wide web. At least how a url (human readable network address) becomes a ip address (a computer readable network address). It bugged me for the longest time what was a domain name or web address. This paper gives the satisfying answer in great detail.
http://www.dtic.mil/dtic/tr/fulltext/u2/a203901.pdf


## Distributed Systems
At this point, you get to two papers that become Hadoop and HDFS. These are moderately technical papers. Though they give enough explanation to keep it grounded, and enough detail that understanding it will be an exercise. https://static.googleusercontent.com/media/research.google.com/en//archive/mapreduce-osdi04.pdf and http://web.mit.edu/6.033/www/papers/gfs-sosp2003.pdf


These were primarily pulled from MIT's software systems class http://web.mit.edu/6.033/www/
