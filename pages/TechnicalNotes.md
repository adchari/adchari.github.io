---
layout: default
title: Technical Notes
tagline: Thoughts on the state of software development
description: Thoughts and Ideas.
---

# Technical Notes

### Clean Code: The Go Programming Language

I've been using Go and learning about its features for the last couple of weeks. The features I find most compelling are the simple syntax and the library features. After programming in C++ for the last two years, standard library packages that are easy to include and use are a must, and the packages I've used so far have been exquisite.

I love `encoding/json` for serializing and deserializing JSON. It's a really straightforward set of functions, and while others have brought up various shortcomings, for the small use cases I had, it functioned beautifully. I also used `net/http` to create an API and play around with some GET/POST requests, and I found it pretty nice that I could set up a very basic API in around 20 lines. The compiler is also blazing fast, and I've heard good things about the package inclusion system.

The simplicity is particularly important here. I truly believe that Java and C++ get a bit hard to read, but moving to a something like Python doesn't solve all your problems. Go gives you a compiled language and static binaries, which will run faster. On top of that, the implementation of concurrency is really straightforward. I wrote my first ever concurrent program in Go, albeit with a little bit of fumbling around, and it was rather successful. It truly is a great language to learn and I intend to explore it further.
