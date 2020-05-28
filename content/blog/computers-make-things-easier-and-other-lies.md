---
path: Computers Make Things Easier! and other lies
date: 2020-05-28T04:12:45.114Z
title: Computers Make Things Easier! and other lies.
description: >-
  Why spend five minutes doing something manually when you can spend 5 hours
  failing to automate it?
---
Ah, so I was struck by inspiration, this weekend. That good-good bug that only comes but once a month or so when I think about something that's fun enough to get me to sit down and start programming. 

What was the task? What magnificent thing did the muse bestow upon me on that blessed Saturday?

Well, I wanted to make it easier to find a cat on Petfinder. And not _just_ a cat, no. A very specific breed and age range (young, Ragdoll; unrespectively). Those things show up on that site and get snatched up so fast that trying to nab one as a simple, pathetic human is nigh impossible. 

Enter: web scraping. Or, more realistically, Chris tries to learn web scraping. So, I started with a tutorial and a library. What tutorial? [This one!](https://www.freecodecamp.org/news/the-ultimate-guide-to-web-scraping-with-node-js-daa2027dcd3/) What library? [Cheerio.js! ](https://cheerio.js.org/) If I could just scrape Petfinder's site, and have it send an alert whenever a new cat was added, we'd be in business. No more waiting around!

Long story short-ish, I got to a point where I was able to pull certain things from the DOM, but because I just didn't commit to really diving into Cheerio's docs, and because I _heavily_ deviated from the tutorial I was stuck. I kept getting arrays full of undefined as responses and I don't think "undefined" is a breed of cat.

And the \*worst\* thing? The most annoying part? 



Petfinder has an API that does the exact same thing. Nice. 



Oh well.
