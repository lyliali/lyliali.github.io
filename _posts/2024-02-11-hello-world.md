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
* anyway that made me think i should get jekyll because i kinda want to bootstrap this website as quickly as possible so i can just start writing entries and tracking my thought development process
* following this youtube tutorial: https://www.youtube.com/watch?v=WhrU9m82Wm8&list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB&index=3
* "welcome to giraffe academy, my name's mike"
* insert youtube university joke
* tried installing jekyll with `gem install jekyll bundler` and failed multiple times
* system output said that the latest version of jekyll uses packages that are incompatible with my os ruby version
* tried updating ruby with `brew install ruby`
* that installed the latest version of ruby but i had no way of changing the system default version without using a ruby package manager
* walked that back, `brew uninstall ruby`
* finally installed rbenv and used rbenv to install the latest version of ruby
* updated system version of ruby with `rbenv global 3.3.0` (the latest version of ruby as of this writing)
* that still wasn't enough to change the system version of ruby and my install was still failing because 
* finally, set latest version of ruby by adding .rbenv/shims to my path: `export PATH="$HOME/.rbenv/shims:$PATH"`

### ok finally
* https://www.youtube.com/watch?v=pxua_1vyFck&list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB&index=4
