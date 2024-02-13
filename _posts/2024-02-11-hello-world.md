---
layout: post
title:  "hello world"
date:   2024-02-11 15:30:21 -0500
categories: 
permalink: /:title
---
# installed ruby oh my god

### why did that take so long?
* ok basically decided my goal is to start a devlog to track my progress and also get my github commit history up.
* because i want to get a job in the tech industry and we're trying to have fun with it.
* anyway that made me think i should get jekyll because i kinda want to bootstrap this website as quickly as possible so i can just start writing entries and tracking my thought process

### "welcome to giraffe academy, my name's mike"
* following this [youtube tutorial](https://www.youtube.com/watch?v=WhrU9m82Wm8&list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB&index=3)
* insert youtube university joke
* tried installing jekyll with `gem install jekyll bundler` and failed multiple times
* system output said that the latest version of jekyll uses packages that are incompatible with my os ruby version
* tried updating ruby with `brew install ruby`
* that installed the latest version of ruby but i had no way of changing the system default version without using a ruby package manager
* walking that back... `brew uninstall ruby`
* arbitrarily decided on `rbenv` as a package manager and used `rbenv` to install the latest version of ruby
* tried setting default version of ruby with `rbenv global 3.3.0` (the latest version of ruby as of this writing)
* that still wasn't enough to change the system version of ruby and my jekyll install was still failing
* finally, issue was resolved by adding `.rbenv/shims` to my path: `export PATH="$HOME/.rbenv/shims:$PATH"`

### ok finally
* https://www.youtube.com/watch?v=pxua_1vyFck&list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB&index=4
* i guess that was worth it?
* i think the edible just hit LMAO
* i learned that github pages does not support jekyll projects in subdirectories
* moved all of my jekyll files into a top-level directory that already existed, using `jekyll new . --force`
* bootstrapped my blog!
* will have to circle back to the theme later and change it cos its ugly

### back to exploring mongodb
* first foray: set up a sample database in atlas free tier
* set up a playground in vscode
* installed `mongosh` in my terminal
* not really understanding how to learn the syntax for interacting with the database in javascript and in mongosh.
* in search of a good tutorial to learn from that's not the documentation.