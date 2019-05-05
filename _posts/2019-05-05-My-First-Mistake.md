---
layout: post
title: My First Mistake
---

The first of many, I expect, and my first attempt at writing a post from scratch.

I was wondering why my site was not updating after I added to the original Hello World post. As I had recently made some changes to the \_config.yml file it was the main suspect. After quite a while I discovered that I made the mistake when entering my Disqus account shortname. Deleting the offending item did the trick and everything is working fine now.

# Addendum #

Just found out that I could have saved myself a lot of time if I had only checked my email. GitHub had helpfully informed me that:  
"The page build failed for the \`master\` branch with the following error: You have an error on line 37 of your  \`\_config.yml\` file."  
Which, of course, is exactly where the Disqus short name is entered.
