+++
title = "It's time to stop using Authy"
date = 2024-07-06T14:27:30+05:30
draft = false
description = "There are better alternatives to Authy"
+++
Authy is a very popular app for storing and managing 2FA(Two Factor Authentication) tokens. When I first started activating 2FA on my accounts, I used Authy to store all my TOTP tokens.

One of the key reasons why I went with Authy is because of its cloud sync feature and their desktop app(which is now discontinued). The cloud sync feature allowed me to access all my 2FA tokens on multiple devices.

But a few months later, I decided to switch to Aegis, a free and open source offline authenticator app. Switching from Authy was a pain because the app doesn't have a feature to export all the tokens. This was super annoying and I hated how they created a walled garden. So I had to go to each of my accounts and then re-enable 2FA and scan the QR code using Aegis.

A few days ago, Authy announced that they were hacked and according to a report by [Techcrunch](https://techcrunch.com/2024/07/03/twilio-says-hackers-identified-cell-phone-numbers-of-two-factor-app-authy-users/), 33 million phone numbers were stolen. 

For a company that focuses on security and providing 2FA related services, this is bad news.

If Twilio (company behind Authy) all of a sudden decides to shut down their Authy service, will you be given the option to export your tokens? I don't think so. It is always better to use an app that gives you full control and freedom.

So what are some alternatives to Authy?
### 1. [Aegis](https://getaegis.app/)

Aegis is an awesome offline authenticator application. It has a nice, clean and easy to use interface and is completely free and open source. Compared to Authy, the app is overkill and offers a ton of features. It even allows you to backup your data and export all your tokens periodically. You can customize it by changing views and using custom icon packs. Also, you can organize and group the tokens as well. 

I have used Aegis for years and it is an excellent choice.

### 2. [Bitwarden Authenticator](https://bitwarden.com/products/authenticator/)

Bitwarden is a popular name among password management services. I have been using Bitwarden for more than  four years to manage all my passwords.

But did you know that Bitwarden recently launched a dedicated Authenticator app?

*The bitwarden authenticator app is a standalone app from the Bitwarden password manager app*

Currently, I am using Bitwarden Authenticator for a change and it is good. Since the app is fairly new, it is kind of barebones and doesn't offer as many features as Aegis.

As of writing this post, the app does not have a cloud synchronization feature (but it is on the roadmap). All the tokens are stored on your device.

If you want to access your tokens on multiple devices, the bitwarden password manager app does allow you to store 2FA tokens along with all your logins. 

### 3. [Ente Auth](https://ente.io/auth/)

Ente is well-known for its  Ente Photos solution, which is a privacy focused open source alternative to Google Photos.

I actually tried Ente Auth after seeing it on Hacker News and my initial impressions is that I really love the app. The app has a beautiful interface and is easy to use. I can  access my 2FA tokens on multiple devices through a browser.

Ente can be considered as the best alternative to authy because of its cross-platform sync feature.

For those of you who want to store the tokens offline, the app allows that as well.

One cool feature of this app that really stood out is that it displays the next token before the current token expires.

### Conclusion
The problem with Authy is not that it is just proprietary but the service also locks you in and makes it difficult for you to shift to another app.

Using the above alternatives puts you in control. There are many more alternatives like Keepass XC that I haven't mentioned. Choose one that suits you.

This is day 33 of [#100DaystoOffload](https://100daystooffload.com)


    



