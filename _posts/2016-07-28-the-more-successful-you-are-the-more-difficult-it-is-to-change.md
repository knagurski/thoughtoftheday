---
layout: post
title:  "The more successful you are, the more difficult it is to change"
date:   2016-07-28 11:30:00 +0100
categories: [tech, programming, "change management"]
blurb: >
  
---
This does have a definite development slant, but I’ve also got a real-world
example, so bear with me. When writing code, you _*never*_ get it right the
first time. As you work on something, you change things and tweak things and
find out what actually works and what’s a bit crap. But what if you aren’t the
only one using those things? The more successful your library, service,
framework, API is, the more difficult it is to make these very normal changes
and the more people will swear vengeance if you do.

If you’re interested in the web dev world, you’ve probably heard of the
[Angular JS][angular] framework. A while ago they were the top-dog and growth
was strong. But they saw problems with version 1 and wanted to change things up
with version 2. So they did. Unfortunately version 2 completely breaks
compatibility with version 1. There is *no* upgrade path and the community is
not best pleased. PHP took a different approach a while back… the developers of
PHP created a function called `mysql_escape_string` and all was well with the
world. Until they discovered that it did a pretty crap job at doing the 1 thing
it was supposed to do. So did they fix it? Nope, they created a new function,
`mysql_real_escape_string`. Lame.

But what about this real-world example? I had my MOT yesterday (well, my car
did... maybe people should as well... another _Thought of the day_) and was told
that my front tyres were pretty close to needing replaced. Any driver in the UK
knows the 20p trick; if the centre 2/3 of your tread is deeper than the band on
the 20p piece, you’re good, if not, get new tyres. But what if the Royal Mint
decided to redesign the 20p? What if the next 20p had 1/2 the thickness of band?
Could redesigning currency potentially cost lives? Maybe we shouldn’t be basing
our measurement on something that is pretty arbitrary. Or maybe I should just
buy some new tyres.

[angular]: https://angularjs.org