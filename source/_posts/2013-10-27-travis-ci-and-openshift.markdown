---
layout: post
title: "travis-ci and openshift"
date: 2013-10-27 23:26
comments: true
categories: 
---

## modern vcs

Recently moved all my stuff from weird place hosted Subversion repo to github and bitbucket. Bitbucket only to host private repos I can't just share around, like previous freelance work, coursera homeworks and stuff. 

## continuous integration

Ok, honestly I'd have more private stuff on bitbucket, but I just couldn't resist goodie-goodies from Travis-CI. Seems that it it __the__ best free cloud based CI option available, due to the deployment options to popular PaaS services and obj-c capabilites. You can also ask for help on #travis when your job hangs, thanks guys. Works just for public github repos in free plan, but that is all I actually need. 

## paas 

Anyway, in efforts to ditch hosting which houses my blog (this one, not there anymore LOL) and Spring Roo stack that powers REST APIs that my iOS apps use, I've begun exeprimenting with Heroku and Openshift. Currently in process of migrating my iOS apps to iOS 7 and relinking urls to Openshift and REST stack is already set-up. What is so cool about it, I don't have to upload war files, which are not famous for their small footprint, no more downgrading JEE Stack to '02 version to be able to run it against Tomcat-5, only option available in cPanel. What?! Wait, what? It's 2013 guys, how 'but a little upgrade.

## blog

I didn't know what to do with hosted wordpress instance that had all my blog entries from Japan trip - only actually valuable thing on this blog. Saw jekyll somewhere, put in action with octopress - still not sure whether to go with twitter bootstrap option or not and hosted it in github pages. Could go with openshift or heroku, but I wanted to save free slugs there for future use, github does good job here.

## era of powerful cli

All that stuff I can do just using command line. Monitor travis buils, deploy to openshift on my own even I have travis configured to do that automatically, write blog entries in markdown. I also started using CocoaPods, xctool for obj-c work, super easy. 
