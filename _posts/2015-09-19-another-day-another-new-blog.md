---
layout: post
title:  "Another Day, Another New Blog"
date:   2015-09-19 -0800
categories: experiments
---
After years of ignoring my blog, I’ve finally decided to get back to blogging again. This time it’s mainly because I want to improve my communication and storytelling skills. For the past decade, my only long form writings have mostly been restricted to reviews and documentations. And I’ve found my story telling skill has severely deteriorated and I’m starting to worry that my imagination would suffer as well. 

Due to years of abandonment, my old WordPress blog is in a state that’s painful to see.

![Ruins of Llanstinan House by ceridwen, cc-sa-3.0]({{site.url}}/images/ruins-of-llanstinan-house.jpg)

Instead of spending the time to upgrade the WordPress instance I have running on my hosting company, I’ve decided to take this chance to do some experiments. (What’s the point of life if without all these little experiments). Since [Jekyll](http://jekyllrb.com/) has been getting all the raves lately, I’ve decided to give it a try. And I’m also going to take a spin with [GitHub Pages](https://pages.github.com/) too, so I don’t need to worry about keeping the site up when I play with other experiments with my hosting account. (And I think I have enough DevOp fun at work already)

Jekyll is basically a simple blog-aware static site generator. It reminds me the good old days of working on Yaoo! Movies where we have a similar generator creating the blogs for special events such as Oscars and Golden Globe and just push the static contents to the edge servers. What database spikes?

Jekyll is extremely simple to set up and run on Mac or Linux, though it takes a little more work to get it working on Windows, which is not officially supported by the Jekyll team. This is really the norm with most if not all things in Ruby… However, there’s [a very helpful step-by-step guide](http://jekyll-windows.juthilo.com/) by @juthilo for Windows users. I pretty much just followed his instructions, except that I need to install Ruby 2.1.7 instead of 2.2.x, because of issues with the wdm gem, and install Python 2.7.10 instead of 3.x because of pygments.rb, which only works with 2.6<x<3.0 at the time of writing. Ah, the compatibility matrix with the microservices model, but that’s a rant for another post.

If you can see this post, that means the Jekyll experiment has (probably) completed successfully.

As for the migration of the old posts, that’ll have to wait for another day...