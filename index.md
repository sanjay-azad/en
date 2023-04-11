---
title: Home
layout: default
nav_order: 1
description: Homepage of blogs from Sanjay Azad
---

<!-- {{ $diff := now.Sub (time .Params.birthDate) }}
{{ $years := div (div $diff.Hours 24) 365 }} -->

{{$age := now.Sub ({{ 'now' | date: "%Y" }} 1994)}}

*Hello,* this is Sanjay Azad. A {{ math.Floor $age }} years old post-graduate from [IIT Bombay], I did my engineering (B.Tech + M.Tech) from the [Department of Electrical Engineeering] with specialization in Communication and Signal processing.


On technical side, I got exposure to [MATLAB] for computational processing and then moved on to [Python] for data analytics. And that's how I started a journey in AI and Machine Learning. I have 6+ years of experience in quantitative analytics, data science and development.


I am passionate about nature, so have developed gardening as a hobby. Except that I am vocal for sustainable development and a critic of rampant usage of natural resources.


I live in India, and have visited several of its cities across states. I believe in connecting with our roots and that we have to strengthen our villages, improvise on agriculture - in sustainability as well as profitability, and keep a check on water and air pollution.


Global warming[^1] is a big threat - not just in terms of rising water levels but also the amount of heat India is facing in past couple of years. This poses a tremendous opportunity to capitalise on the excess energy we are receiving from the sun.


Indian culture and history has been a source of fascination to me. Its traditional and ancient knowledge system woven into the fabric of mythology and religious philosophies are astounding. They can prove to be a disruptive technology for human cognition in today's world of chaos and sufferings.


I am a student of science and is a proud critical thinker and seeker of knowledge.


The information, facts and theories that I have acquired over my life period - those are my assets, and I am willing to disseminate them over here to a larger audience. The blogs are going to be from diverse background, but mostly will have following flavours:

- Finance
- Machine learning
- Deep learning
- History and polity
- Nature and Agriculture
- Indian culture and philosophies


----

[^1]: [Global warming is a big threat](https://www.nrdc.org/stories/global-warming-101).

[IIT Bombay]: https://www.iitb.ac.in/
[Department of Electrical Engineeering]: https://www.ee.iitb.ac.in/
[MATLAB]: https://www.mathworks.com/products/matlab.html
[Python]: https://www.python.org/

