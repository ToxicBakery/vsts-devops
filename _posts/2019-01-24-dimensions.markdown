---
layout: post
title:  "Clarification"
date:   2019-01-24 08:40:00 -0500
categories: microsoft devops
---

A few people have questioned the screen dimensions complaint from my original post so I wanted to take a moment to clarify exactly what I meant.

![DevOps Is Down]({{ site.baseurl }}/images/screen-dimensions-1920-too-small.png)


In this image I scaled a browser window up to ~1920 pixels wide and used the dev tools to describe the rendered window giving 1905 pixels for content to be rendered. At this width, two columns of information are still missing from the pipeline history display: Repository and Queue. Repository is less important for my use case as it is always blank but Queue is important to me. Working from my laptop, the only way for me to see that column is to oversize my browser window.

