---
layout: post
title: "Tech-Knowledge"
date: 2014-05-21 18:45:00
categories: projects ereader
---

After almost no thought, and a *little* consideration, I've put together a few
technologies I'll be using to create this ereading software. Some of them I've
used before, some of them I've just discovered through research. I think all of
them are appropriate for this project, but frankly I've had so little experience
with some of them I just don't know. Still, no reason not to dive in.


## The Platform - [node-webkit](https://github.com/rogerwang/node-webkit)

This is something I've been itching to work with for a while. As a full-stack
web developer with a focus on [JavaScript everywhere](http://nodejs.org), I'm
most comfortable building UI using `HTML` and `CSS`, and controlling everything
back- and front-end using `JavaScript`.

It's a *crude description*, but `node-webkit` is a webkit browser that is used
to display your application and run what would traditionally be your server-side
code on the client. This means you can build stand-alone apps with the same
technologies you'd usually use when building a website.

## The Database - [PouchDB](https://github.com/pouchdb/pouchdb)

A pocket-sized `NoSQL` database. NoSQL refers to the fact that, unlike
traditional databases, the data is not stored in tables, and is not relational.
I've never used a NoSQL database before, but it looks like the data for this
application needn't be relational, and it's a good time for me to learn all
about it.

As I understand it, PouchDB is embeddable and therefore doesn't require a
database server to be running. However, as my first time dealing with this
software and having only had a cursory look at their github page, I *may* be
wrong about this.

## The Front-end - [React.js](http://facebook.github.io/react/)

I've been prevented from using this anywhere other than small experiments by the
fear of everything being controlled by JavaScript when someone could come along
with an out-of-date browser or JS disabled. When I have used it, however, I
loved it.
As this app will be using node-webkit, I can be sure of the environment the
front-end will be deployed in, and so this is less of a concern.

In short, React allows for data-driven UI that uses a Virtual DOM to generate
and render changes quickly and in only the places that need it. It also provides
a pattern for creating UI Modules in the same way you'd create them in the back-
end.

## Other



There's some other stuff that I'll be doing too. For one, I'll be writing in
`CoffeeScript` rather than JavaScript.I'm pretty new to the concept of
transcompiling from one language to another, and was somewhat pushed into it by
my desire to make my [atom](https://github.com/atom/atom) editor work like I
wanted it to, but so far my experience has been so pleasant that I want to write
any new work in CoffeeScript.  


I've also been trying to get a handle on
`Behaviour Driven Development`, and exposing my attempts at being strict about
testing my code to the public might just give me the push I need - and any
pointers about how I'm doing it *so* wrong are very welcome. 

I think all that's left is to make a repo and start coding. I would think that
my next post will contain actual *getting down to business*, and may even
contain some code - I need to set up all the tech into a basic, functionless and
hollow shell.
