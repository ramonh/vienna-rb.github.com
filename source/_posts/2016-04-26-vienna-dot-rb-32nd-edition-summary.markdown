---
layout: post
title: "Vienna.rb 32nd edition summary"
date: 2016-04-26 21:51:59 +0200
comments: true
categories:
- meetup
- recap
---
Oh hello! Didn't see you come in. If you couldn't make it to our last meetup, have we got a treat for you! We had three great talks given by three great speakers that you'll find out all about below:

## Our Talks

### [Aaron](https://twitter.com/mraaroncruz): Ruby Alternatives

We begin with Aaron's talk, which he previously gave at [RubyConf India 2016](http://rubyconfindia.org/), on how he's looking into moving forward from the current state of Ruby and concurrency (not much to see there, it seems). He therefore showed us three of the languages he's been playing with: Go, Elixir and Crystal.

#### [Go](https://golang.org/)

Go is a compiled language that came out of the need at Google boasts its speed, simplified dependency model, lightweight static type system and multi-core-first approach. It employs Go routines and channels for threading and semaphores, respectively.

#### [Elixir](http://elixir-lang.org/)

Elixir, which runs on the Erlang VM, was born out of a desire to address the problem of concurrency in Ruby, as well as adding improvements on top of Erlang by José Valim. On top of that, Aaron recommends checking out Erlang movie, which you can find [here](https://www.youtube.com/watch?v=xrIjfIjssLE). 

This language is functional and is built with a focus on concurrency up front. It's also fault tolerant and has a pretty great read–eval–print loop (REPL) program.

Elixir's [Phoenix Framework](http://www.phoenixframework.org/) is something also worth of note. It's the language's equivalent to Rails, and comes with its own routing, controllers, and the other good stuff that comes with it!

#### [Crystal](http://crystal-lang.org/)

Crystal is also a compiled language that aims to be as similar to Ruby as possible, and tries to have the user never have to specify types. It offers compile-time evaluation and generation of code.

Aaron then showed us what was practically Ruby code running in Crystal and several times faster, at that!

The language is currently in a "Very Alpha" stage and we're all encouraged to try it out or donate. In fact, Aaron introduced us to an equivalent for MINASWAN, which is as follows:

	MDTCASWDTC: Matz Donates to Crystal and so We Donate to Crystal.

Aaron wrapped up his talk by encouraging us to run exercism.io exercises and check out more resources on [his website](http://aaroncruz.com/ruby-alternatives). Thanks Aaron!

## [Dave](https://twitter.com/dch__/): An intro to distributed systems

Our next talk comes from Dave, who starts with a story of a text message that took a month to make its course. 

Dave presented the challenge of explaining what the concept of a system being "Eventually consistent" (that is, having all accesses to an item in a system eventually returning the latest value) really means, or whether it's nothing more than a marketing blurb.

He also took us through the famed [8 fallacies of distributed computing](https://blogs.oracle.com/jag/resource/Fallacies.html)

