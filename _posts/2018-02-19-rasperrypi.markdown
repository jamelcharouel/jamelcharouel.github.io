---
layout: post
title:  "The Raspberry Pi"
date:   2018-03-06 8:57 PM
categories: projects
tags: personal, projects, rasperry, pi, sonarr, radarr, pihole
---

   My parents have been asking me this question a bunch lately: "Seen anything good on Netflix?". I use Netflix strictly for binge watching originals, so my suggestions are usually limited. I decided to solve this problem by looking into ways to set up a media streaming server on the cheap; that way, I can throw a bunch of media on there and my parents can watch whatever they want to their hearts content. After doing some research, I decided to get a raspberry pi to start out. 

   Let me say, this thing is awesome. The pi itself with the all of the works (SD Card, case, extra HDD) cost about $100. Most NASes bought fully set up cost at a minimum $200 and can get more pricey depending on performance/storage space, so this was a great compromise. While the pi isn't a complete powerhouse, it works for being an additional network drive or streaming server when I need it.

   In terms of the software I've got on the pi to run the streaming server, I use Raspbian Stretch as the OS on the pi, [Samba](https://www.raspberrypi.org/magpi/samba-file-server/) in order to create a network drive on my home network, and [Plex](https://www.plex.tv) in order to stream content from the pi to a phone or TV. Setup was relatively quick once I realized that unplugging your pi without giving it a shutdown command corrupts the booting process... :D

   This setup makes it easy for my parents to continue to use their phones and TV the way they have been after I got them a Chromecast. On my end, I just have to add media and let them know that I've added new movies or shows that they wanted to watch. You can also set up your pi or a separate PC with Radarr/Sonarr to have the ability to automate this process, making it so that anyone can just search for media they want to add on their phone or PC but I totally, definitely, don't know anything about that.

   In addition to the streaming server, I use my pi for filtering my home network traffic. I've set up [Pi-Hole](https://pi-hole.net/) on the pi so that ads from known blacklists are automatically blocked. This effectively speeds up my internet and keeps my family protected from pesky, possibly malicious advertisements.   The great thing about the pi is I've set it up to be headless, so I can simply do everything I need on it from my main PC. If I need to alter some settings or check its performance, I simply ssh in and go.

   Anyways, thats all for now. If anyone has more suggestions for software to throw onto my pi, let me know!

--- Jamel Charouel

Tuesday, March 6th, 2018
