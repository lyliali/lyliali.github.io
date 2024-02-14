---
layout: post
title:  "hello world"
date:   2024-02-11 15:30:21 -0500
categories: 
permalink: /:title
---
# hello world!
* My goal is to start a devlog to track my upskilling progress and also get my github commit history up.
* I decided to set up my blog with jekyll because it seemed like a fast and easy way to bootstrap my website, so I can get straight to writing entries and tracking my thought progress.

### "welcome to giraffe academy, my name's mike"
* First step to bootstrapping myself with jekyll: Installing it.
* Like a good YouTube University alumn, I searched up a [youtube tutorial](https://www.youtube.com/watch?v=WhrU9m82Wm8&list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB&index=3) to follow.
* Tried installing jekyll with `gem install jekyll bundler` and failed multiple times
* System output said that the latest version of jekyll uses packages that are incompatible with my OS ruby version.
* Tried updating ruby with `brew install ruby`
* That installed the latest version of ruby but I had no way of changing the system default version without using a ruby package manager
* Walking that back... `brew uninstall ruby`
* Arbitrarily decided on `rbenv` as a package manager and used `rbenv` to install the latest version of ruby
* Tried setting default version of ruby with `rbenv global 3.3.0` (the latest version of ruby as of this writing)
* That still wasn't enough to change the system version of ruby and my jekyll install was still failing
* Finally, issue was resolved by adding `.rbenv/shims` to my path: `export PATH="$HOME/.rbenv/shims:$PATH"`

### why did that take so long
* The mantra of every software developer. Even the simple tasks can throw you for loops!
* The [video I referenced](https://www.youtube.com/watch?v=pxua_1vyFck&list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB&index=4) to learn how to create a new website with jekyll.
* I learned that GitHub pages does not support jekyll projects in subdirectories, which was a problem for me because I created my new jekyll project in a subdirectory of a GitHub pages repo I had made previous to this writing.
* Moved all of my jekyll files into a top-level directory that already existed, using `jekyll new . --force`
* Bootstrapped my blog!
* Will have to circle back to the theme later and see if there are other appealing aesthetic choices.

### back to exploring MongoDB
* Another interest I have is learning MongoDB as it is a common backend in the front-end web stack.
* For my first foray, I set up a sample database in Atlas free tier
* Set up a playground in vscode
* Installed `mongosh` in my terminal
* We'll leave it here. Til next time!