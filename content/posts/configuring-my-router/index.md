+++
title = 'Configuring my router'
date = 2024-05-15T21:37:00+05:30
draft = false
description = "I changed a few settings on my router"
+++
I got my hands on a new used router and I spend some time configuring it. Lets go!

1. Turned off WPS

    WPS is a feature which allowed you to connect to a network without having to enter a password. All you had to do was push the WPS button on the router and enter WPS mode on your phone or device and tada!. You are connected.

    The big problem is that anyone who has physical access to your router can just push the button and connect. I once remember my friend who came to my home and went straight for the router without asking me the password or anything and connected his device to it by using the WPS button. This kinda freaked me out. 

    But now, WPS is considered insecure and everyone recommends you to turn it off. If you still have it turned on, disable it. Newer devices don't even have the option to use WPS.

2. Changed the DNS Servers

    I changed my default DNS servers to [Quad9 DNS](https://www.quad9.net/). The DNS server provided by your ISP may be slow so it is a good reason to change it. I specifically chose Quad9 as it has good malware blocking so that I can browse the web safe and secure. You can use other options like Cloudflare, NextDNS and so on.

3. Changed the default SSID and password and changed the credentials for the admin panel

    This is really obvious. Using the default password provided by the ISP and the default credentials provided by the router manufacturer is not a good practice.

4. Disable uPnP

    uPnp is short for Universal plug and play and I don't really know what it is or use it. So I disabled that as well.

5. Connected my printer
    I also connected my dumb USB HP Printer to the router and now my printer acts like a wireless printer. This is probably the thing I am most happy about. 

    The router I used earlier did not have a USB port. But now with my current router, I can print documents over the network...Yay!

Yeah, so these are all the small changes I made. I wish I could configure a guest network but that is not a feature on my router model.

In the future, I might get my hands on a router which can run OpenWRT so I can have more control.

What settings do you change when you get a new router? I would love to know.

This is day 25 of [#100DaystoOffload](https://100daystooffload.com)