---
layout:	post
title:	"I wish I knew this"
date:	2014-01-21 6:43
categories: windows jekyll
tags: windows jekyll ruby tips
comments: true
---

A tiny selection of tips for those who are determined enough to want to use jekyll on windows.

+ Downgrade jekyll from 1.4.3 to 1.4.2 (`gem install jekyll --version "=1.4.2"`, then gem uninstall 1.4.3).
+ Also downgrade pygments from 0.5.x to 0.5.0.
+ **Use Ruby 1.9.3**.
+ Add a python installation to your PATH.
+ Use [RailsInstaller](http://railsinstaller.org "RailsInstaller by EngineYard") to install Ruby.
+ use `gem uninstall .. --ignore-dependencies` to move past "[..] one or more dependencies will not be met."	
+ keep a windows shell open with `taskkill /IM ruby.exe /F` (actually terminates ruby.exe).
    + Press the up key in cmd.exe to grab the previously executed command.

### References


1. ["Using Jekyll with Pages by Github"](https://help.github.com/articles/using-jekyll-with-pages) - jekyll help by Github. Especially applicable if you're publishing your site on there.
2. ["Installing Jekyll on Windows by Chris Meserole"](http://chrismeserole.com/coding/install-ruby-rails-jekyll-on-windows/) -  blog post that sets apart two ways to install jekyll on windows.


