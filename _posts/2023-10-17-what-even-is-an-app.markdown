---
layout: post
title:  What even is an app anyway?
description: Understanding what an app is and how it works.
date:   2023-10-17 15:01:35 +0300
image:  '/images/02.jpg'
# video_embed: https://www.youtube.com/embed/gghgYaYeG_M
tags:   [app architecture, ios basics]
---
# Introduction
When you first get started in your career you learn that you use Xcode as your IDE, you learn the basic building blocks of Swift, and how UIKit (SwiftUI for you new devs) can be used to forge our UI together. You press the play button in Xcode and *hope* that the iOS Simulator opens something that resembles what you had in mind. But what's actually going on here? What even is an app to begin with? 

Taking a step back from code, when using apps on our Macs or iPhones we simply click/tap to launch them, but what are we actually doing? We could guess that the app involves some kind of binary but is the app icon itself the binary? Is that what we're tapping when we open an app? 🤔

# ‌A look under the app icon
If we examine our MacOS dock we can start to gather some clues as to what these apps are. Let's open Finder and navigate to our Applications directory. From here, we can Right Click an application and take a look at the menu options provided to us.

![Right clicking on an App Icon]({{site.baseurl/images/01-01.png}})
*Right clicking on the App Store icon in the Applications directory.*

We can see an option labeled `Show Package Contents` - this seems to suggest this is a package of sorts. What exaclty is a package?