---
layout: post
title: Useful Jekyll Commands
date: 2021-12-12 16:54 +0530
---

## What this isn't about ?
This page isn't going to list out all the commands related to Jekyll static web-page craetions

## What is this Post about ?
This page is going to provide the most useful commands that I felt while creating Jekyll static web-pages.

## Few Useful Commands

#### Installing gem packages
``` bash
gem install <package-name>
```

#### If a new configuration has been added to the _config file
``` bash
bundle install
```

#### Create new Jekyll site
``` bash
jekyll new <site-name>
```

#### Create new Jekyll post
``` bash
bundle exec jekyll post "<post-name>"
```

#### Build Static Pages
``` bash
bundle exec jekyll serve
```

#### Auto refreshing/reloading of the pages
``` bash
bundle exec jekyll serve --watch (works on powershell!)
```