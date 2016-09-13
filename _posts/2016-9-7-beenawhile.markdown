---
layout: post
title:  "It's Been A While"
date:   2016-09-07 10:16 PM
categories: blog
tags: trips, summer, vacation, school
---

It's been quite a while since I've last made an update to this site. I was pretty busy last semester as well as this summer gearing up for my final year at UVA and figuring out what I wanted to do with my last "true" summer as a student. Two years ago I told my mom that once I graduated my life would be over and I would have no time to do anything since there were no real breaks when you work full time. I found out that that wasn't too true, but the summers where I did nothing will be sorely missed. I'm going to make this post about my summer that included a sizeable amount of work, and I'll make the next about my vacation which included a sizeable amount of play, proving my past-self wrong.

This summer I worked at Novetta again for the second year running. Instead of running through the Android app development lifecycle from end to end like last year, I worked on two medium sized projects that ran about a month each. The first was a conference calling application that allowed users to log on to a site on the Novetta servers and make video conference calls as well as persistently chat amongst groups or individuals. Persistent chat was the key here as it was important for the users to be able to be offline or have no signal while still being able to receive messages once they came back online. The challenge with this application was putting together the pieces that it incorporated. It involved using Matrix, an open source group messaging service, in tandem with Freeswitch, a calling service, and Verto to bridge the two to allow video conference calling all served up from Novetta servers. All in all, it was a pretty complicated system with a lot of moving parts. I learned a lot about networking and the work it takes to integrate several servers with several different services. I had to set up a TURN server to forward calls from the conference calling bot on the Matrix server to the other users on the server. How it worked was one user made the request to create a video conference call, and the other users in the chat room chose to accept or not. If they accepted, the bot would connect them to the video call for the room.

The second project I worked on was a small Android application that allowed a user to stream and broadcast their video stream across an internet connection; the aim for the project was to broadcast over a VPN. While it sounded daunting at first, I was able to use the Libstreaming video streaming library to do most of the heavy lifting for me. The programming mostly involved using the library to create a stream, and then figuring out how to broadcast that stream over the VPN connection on the Android and view it on a computer also connected to the VPN. This project involved a lot of networking knowledge as well, and the first project of the summer made it a bit easier to complete after I had learned the ropes.

All in all, I had a great time again working at Novetta and working with the people on the mobile development team. I took a probability night class while working which added some extra exhaustion to my weeks, but it was worth it in order to have time in my final year to work on my personal projects and the job search.



--- Jamel Charouel

Tuesday, August 7th, 2016
