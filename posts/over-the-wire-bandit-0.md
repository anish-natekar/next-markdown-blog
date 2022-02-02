---
title: 'overthewire wargames bandit 0'
date: 'Feb 2, 2022'
excerpt: 'overthewire wargames are interactive command line challenges which are used to teach cybersecurity concepts. The Bandit wargame is aimed for absolute beginners'
cover_image: '/images/posts/otwnew.png'
---

Hi people :) , I'm Anish.

Over the weekend i found myself watching many videos/TV series related to cyber security and I got extremely motivated to learn more about it.

Turns out cyber security is a vast field, notoriously difficult and through my past CTF experiences I have found it to be very demotivating :( .

In my Freshman I was taught Linux commands but a few months Later I have forgotten most of them :'( . I had heard about some online websites which are good for beginners such as tryhackme and OverTheWire. I had already completed the tryhackme Linux fundamentals rooms long ago so I decided to do the OverTheWire Bandit challenges this time.

Website: https://overthewire.org/wargames/bandit/bandit0.html

Level zero gives us a brief description about the bandit series of labs and that we need to find passwords in each level to proceed on to the next one. All levels will be accessed through the terminal using secure shell AKA 'ssh'.

for level 0 we just need to ssh into their server 'bandit.labs.overthewire.org' on port '2220' with the username 'bandit0' and password 'bandit0'.

The ssh command will look like this:

```
ssh -p 2220 bandit0@bandit.labs.overthewire.org
password: bandit0
```
With this you have completed Lv 0 and have entered the server where we will do all other levels.

The only thing we need to take away from this is the ssh command that we use for the other levels will only differ by the level number (the 0 in bandit0) and password that we need to find.

Thanks for reading my writeup :) . Stay safe, byebye.
