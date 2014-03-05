---
layout: post
title: "Android Studio, First Impressions"
date: 2014-03-05 10:43:08 +0530
comments: true
categories: android
published: true
---

Android Studio is this shiny new IDE by Google, that was announced during the Google IO 2013 last May. It is built on top of the community edition of IntelliJ IDEA, and is expected to replace the currently used _Eclipse + ADT bundle_ distributed with the Android SDK.  

{% img http://i.imgur.com/LR5Vffa.png %}

It's been in its beta stages ever since, so there is still a resistance among developers to move their projects from the god-forsaken old eclipse. As I was starting a new project, I thought when better to start working on Android Studio than its version 0.4.6 , right ?

Ok, so I did. And here goes my initial experiences. I had installed Android Studio long before, when it was in version 0.2.0, but never bothered to use it afterwards. When I opened Android Studio, I got a pop up message about the update to Android 0.4.6 .

{% img http://i.imgur.com/M6DOmMK.jpg %}

Now, having had many nightmarish times updating eclipse on my linux machine, I was kinda reluctant to do this update. And the message about the canary builds did not help either (see image above). But anyway, working on version 0.2.0 was not an option. So I went ahead and clicked the update button.

Having done this, I have to tell you how surprised I was by the update process. It was really simple and as easy. Hitting the update button was all I had to do. If you are wondering why I am being so skeptic about updating a damn software, well having used Arch Linux for a long time in the past, I have some painful memories with software breaking everytime I started working on a new technology.

Creating a project on Android Studio was fairly straight forward. If you have used eclipse, it's no different from ADT. However, after creating multiple projects, I noticed the concept of ***module vs project***.

Turns out, there are no workspaces in Android Studio. Doing [some research](http://stackoverflow.com/questions/17187080/android-studio-new-project-vs-new-module), I found that
> Whatever you do in IntelliJ IDEA, you do that in the context of a project. A project is an organizational unit that represents a complete software solution.

> Your finished product may be decomposed into a series of discrete, isolated modules, but it's a project definition that brings them together and ties them into a greater whole.

Or, 
> *Module* in Android Studio is like a *Project* in Eclipse
*Project* in Android Studio is like a *Workspace* in Eclipse


During the initial run, I encountered an error where I had to update my Gradle build file to gradle-1.10-all.zip . It was quite a hurdle, but the awesome community at Stack Overflow always make it easy for you to get on with your project ! 

I don't intend to switch to eclipse again, I hope Android Studio treats me well :)