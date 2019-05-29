---
layout: post
title:  "Significant Improvements All Around"
date:   2019-05-28 02:50:00 -0500
categories: microsoft devops
---

It's been a few months and I'm happy to say using ADO is enjoyable now. Many features have been measurably improved and old issues have been eliminated and minimized. I would like to thank Microsoft, most notably Chris, for their support, feedback, and guidance.

### Pipelines

Pipelines are the new method of viewing builds which can be enabled via the `Preview Features` panel under your user avatar. This screen is now responsive, shows generally all of the build data from a quick glance, and even works generally well on mobile. It still needs some work for mobile but it's much more usable now and I was assured more improvements are coming over the next few release cycles as they work towards full release.

![Pipeline on Desktop]({{ site.baseurl }}/images/measured-improvement-pipelines-desktop.png)  
*Example from a desktop*

![Pipeline on Mobile]({{ site.baseurl }}/images/measured-improvement-pipelines-mobile.png)  
*Example from a phone*

### Dark Theme

From the screenshots you may have noticed something simple yet greatly appreciated. ADO has a dark theme. While this still has some minor issues on some screens and extensions, overall this is a welcome change for those that prefer a darker look. If it's not for you, no worries the light theme remains the default.

### Stability

After working with Chris and his team for on a few build issues I'm extremely happy to say we have multiple build pipelines now that are all stable and issue free. Our process hit several edge case issues and after feedback, it appears, these have all been resolved.

### Caching

One of my bigger complaints was a lack of a caching system. Reading around I know a lot of developers had similar issues with the CI implementation and it's lack of cache functionality. While not yet released, a cache implementation has been merged and will become available in the coming months.

Reference issue: [azure-pipelines-yaml/pull/113](https://github.com/microsoft/azure-pipelines-yaml/pull/113)
