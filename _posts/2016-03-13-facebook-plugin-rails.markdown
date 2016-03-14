---
layout: post
title:  "Facebook Comment Plugin in Rails"
date:   2016-03-13 23:05:55
categories: web, rails
location: Houston, TX
tags: web rails
---

For the video website I am creating we wanted to add some commenting options. The Facebook Comments plugin works nicely for our needs.
It is easy to add. Looks half decent. And the visitors don't need to create yet another account (if they have Facebook).

But I was running into a problem that when the page was loaded the comment plugin would not show, until I refreshed the page.
Turns out there may be a problem with Turbolinks and JavaScript. I found the solution on StackOverflow, but that didn't have much detail.
I will probably run into something else that will provide more insight soon.


Read this on StackOverflow [here](http://stackoverflow.com/questions/23773804/facebook-comments-plugin-showing-only-after-refresh).

