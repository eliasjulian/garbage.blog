---
layout: post
title:  "🛠 Building & Scaling a Design Language"
date:   2016-02-10 18:15:15 -0500
categories:
---


![design language mockup](/assets/img/designlanguage1.jpg "design language mockup")

## Oooooh design languages

Usually design trends are head scratchers at first glance, a few weeks later they start to show up in your work, a few more weeks pass and something else new and weird comes along, that also slowly starts to appear in your work, and outside of the vague influence they’ve had, they fade into oblivion. And the cycle continues. Or maybe that’s just my experience. Regardless, all along the way little bits and pieces stick around. It may be too soon to really tell, but I think the design language is different. And it’s because it’s not a new concept. It’s recent rise to internet stardom is merely a symptom of the ever-expanding need to design for every medium and platform under the sun. And for good reason. Without a design system or common visual language, it’s extraordinarily difficult (dare I say impossible) to stay visually consistent and current when you’re creating for different screen sizes and platforms at scale. Oh, and doing so while you’re facing unforgiving deadlines.

Working on a small team, means a lot of times we have to ship quick, one-off solutions. Unpredictability and urgency is often the nature of the business. That’s not to say that these quick solutions are bad or temporary by nature, but without ever learning and changing (and getting feedback from real people) we end up accruing a whole lot of design debt along the way. And that leads to losing touch with your user base, which is never a good thing. A design system can help ease that pain.

## Y’all still with me?

Trends come and go all the time. The design language is different. (I think) Design languages help with staying consistent and current at scale. Design debt accrues [quickly and quietly](https://youtu.be/DQ1CgPYRqVo).

![design language screenshot](/assets/img/designlanguage2.png "design language screenshot")

**1 — Sketch**
We have one master Sketch file that holds all visual components. A few pieces that should always maintain the same size & padding are Sketch symbols, like headers and legal copy, but most elements live on their own artboards. Reason being that the language is supposed to be flexible (i.e. adaptable) and resizing one instance of a symbol in sketch will resize all instances of that symbol, which freezes up your machine for a minute and messes up all your designs in that file.

**2 — Github**
We use Github as a changelog since there are a few different people iterating on the same system. For each update, you start a pull request that’s accompanied by .png exports of the new and improved elements paired with a short explanation of what’s changed and why.

**3 — Dropbox**
After the pull request request is approved, the updated sketch file is added to a shared dropbox folder where it’s available for everyone to use instantly. And, should anything happen to that file, dropbox supports versioning, so we can revert back to a previous version of the file.

*📝 originally written on 02.10.16 — I’m moving a lot of things over from an old blog to have a single home for my posts*
