---
layout: post
title: Burp Suite Certified Practitioner Review
---

Well, after studying for about 4 months, I've finally passed and got the certificate for Burp Suite Certified Practitioner.
Below you'll find my review on it.

### So what is it?
Burp Suite Certified Practitioner, for short BSCP, is a certification where you'll be able to demonstrate your web testing skills. It covers a wide range of topics, from XSS, SQLi, SSTI and others.

### Background
For anyone just dropping by this post, I work as a full-time pentester, almost all my tests involve Web applications. So I'm familiar with the most common vulnerabilities.
Nonetheless, this exam was not easy, I did not pass on my first try :(  but did on my second try (which was the day after).
My interest on web app testing spiked the last year which prompted me to work for this certification, the more I learned the more interested I became.
So I made it my goal to complete this certification during this year of 2024.

### Preparation
I really did not have any format of studying per say, for example organizing study topics and going for it that way.
I just went down the list of topics and did exercises from Apprentice to Practicioner and then moved topic.
Took notes along the way, which came very handy during the exam! (Some payloads were **almost** copy and paste!)
By the end of it, this was my preparation:

<img src="../images/BSCP_Progress.png">

### Exam Experience
#### First attempt
My first attempt was on a Saturday, I was feeling very nervous which impacted my exam experience in the end.
So it begins with proctoring by Examity, they just basically verify your identity and then leave you alone, there's no one proctoring you the whole exam like OSCP.
After proctoring finishes you're good to go and they give you 2 apps, three stages each, just like the practice exam.

Foothold took way longer than expected, 1 hour into the exam I had nothing. So I started looking to both apps at the same time desperately trying to find a foothold.
I eventually got it on both and started working on App 2 because it seemed easier.
App 2 was actually ok'ish, I ended it with around 90 minutes left on the clock, **not good**.

Went back to App 1 and just did not make it past foothold.
Looking back I probably know what I had to do, but the last hour I just felt like giving up.
So it ended like that, I got stuck at 4/6.


#### Second attempt
After a night's sleep, rest and contemplation, I built enough courage to try it again, I was more confident I could pass now that I've failed, but at the same time it was becoming costly.

The apps you get are (supposedly) random, but I did get some repetition. My second app had 2 stages that were the same as the ones from the first attempt, so naturally this time, I blazed through it. The first app got it done in 1 hour and the second one just under an hour as well.
So from beggining to finish it took me around 110 minutes for the whole exam.

There was only a step in foothold again that took me longer because I was making wrong assumptions. Oops!

<img src="../images/BSCP.png">

### Final Thoughts
I enjoyed it.
A challenging exam for sure, I learnt alot but not from the exam but from the academy itself, what made the exam difficult, in my opinion, was the time pressure. 4 hours seems like alot until it doesn't and you see the time decreasing with no progress, your confidence takes a hit and it goes downhill from there.
So, be well prepared for the exam, make sure you have your notes ready and your guns loaded (burp extensions)

### Tips
- Don't rush preparation
- Active Scanner is your friend
- Be sure to load your extensions (they help with scanning!)
- Learn data exfiltration techniques
- SSRF is always on localhost:6566
- Read [this](https://portswigger.net/web-security/certification/how-it-works)
