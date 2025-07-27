---
layout: post
title: "AWS Ate My Free Time (But I’m Not Mad About It...)"
date: 2025-07-27
categories: devops learning journey
---

Some people binge Netflix, I binge AWS. Over the past few weeks, it’s been my daily companion, and I’m now about 90 hours deep into the SAA course—complete with my Obsidian notes that looks like a cloud architecture crime scene.

The good news? The information is sticking. I’m scoring well on the section quizzes, and the concepts are starting to feel clear and intuitive. I owe a lot of that to Adrian Cantrill, who’s an exceptional teacher. His detailed diagrams and visual explanations are not only engaging but also make for quick reviews, helping me cross-check my own notes for accuracy.

I’m also planning to dive into Stéphane Maarek’s course on Udemy, which I’ve heard is much more exam-focused. I think it’ll be a good way to measure just how solid Adrian’s content is while giving me another perspective on AWS architecture and best practices. I strongly believe getting two different sources / teachers for concepts is crucial to learning something deeply. The same points explained by different people can have a meaningfully different impact on the way the information is memorized.

This week, what really stood out to me was how services like CloudFront, S3, Lambda, and API Gateway work together to create a highly optimized, globally accessible application. I love the fact that with AWS, you’re not just drawing up architectures like a building architect—you can actually build what you design. That combination of creativity and practicality is what makes cloud architecture so compelling to me.

On the Linux side, I’ve been taking full advantage of the 750 free AWS tier hours by running a test machine 24/7. I replicate everything I see in the videos, which has made me much more comfortable with fundamental operations. File permissions, which used to feel like a puzzle designed to hurt my brain, are finally starting to make sense.

And then there’s SELinux. Honestly, I didn’t like it at first—it felt overly complex and strict. But after tinkering with it, I’ve come to appreciate its design. It’s surprisingly logical and very effective once you understand the basics.

One thing that struck me is a point the course instructor made: if SELinux were implemented at scale, data leaks would drop dramatically. That raises the question—why isn’t SELinux the default on Ubuntu like it is on RHEL or CentOS?

What’s your take on SELinux?

I’m curious to hear from those with more hands-on experience: would you make SELinux a standard part of your Linux setup? Have you found a sweet spot between security and flexibility, or is there another tool or approach you’d recommend? I’d love to hear your stories, especially from anyone who’s balanced SELinux in a production environment without going full overkill.
