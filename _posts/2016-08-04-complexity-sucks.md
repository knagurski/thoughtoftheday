---
layout: post
title:  "Complexity sucks"
date:   2016-08-03 22:00:00 +0100
categories: [tech, programming]
blurb: >
  Making things simple does not mean they're dumb. Often it's harder to make
  something simple than it is to make something overly complex
---
Complexity for complexity's sake is dumb. All too often in the PHP development
space (and others for that matter), we get held up on the [SOLID][solid]
principles.

## What's wrong with SOLID?
Don't get me wrong, [SOLID][solid] is a good target for development, but you
really do need to bake in some common sense as well. If you follow these
principles to the extreme, you end up with compact classes, doing a single task,
all easily swappable, making it great for testing. But what you also end up with
is dozens of files, each so decoupled that following through a debugger is a
nightmare.

What you lose with over SOLIDing a codebase is understandability; with so many
files, it's difficult to get an overview of what the thing actually does!

## So what's the solution?
As I said, I don't disagree with [SOLID][solid], but I believe that the
intention of these principles is to reduce complexity, not increase it. So the
solution is to make smart decisions about the _ACTUAL_ code you're writing, not
parrot a book you read.

Does that simple thing really need another class just so you can abide by the
_Single Responsibility Priciple_? Probably not. If it makes sense that that
functionality sits in a certain place, let it live there.

What [SOLID][solid] aims for is a perfect ivory tower of code, but what Agile
and refactoring push us towards is starting simple and introducing complexity
only when needed.

So read up on [SOLID][solid], understand what they're trying to guard against
and refactor in that direction, but use some common sense, does introducing
complexity _HELP_ your code, or _HURT_ it? Maybe we should start a pragmatic
programming movement and stop shaming code that breaks what (I think anyway) are
good suggestions, not rules.

[solid]: https://en.wikipedia.org/wiki/SOLID_(object-oriented_design)
