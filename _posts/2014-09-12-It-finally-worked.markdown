---
layout: post
title:  "It finally worked!"
categories: Diary
---

So happy!!

It could not generate the site locally at first, giving the information:

`spawn.rb:164: warning: cannot close fd before spawn...`

It may be caused by the default highlighter the jekyll uses. It can be fixed by doing:

`gem install rouge`

and then add a new line:
`highlighter: rouge`
to the _config.yml

I found the solution [here].

[here]: http://stackoverflow.com/questions/16498287/jekyll-liquid-exception-cannot-load-such-file-yajl-2-0-yajl

