# Learning Icon

This repository is part of my newsletter project, learning Icon and sharing interesting things I've found. [Check it out](https://coreyhaines.substack.com/)!

## Goal

The current goal is to build a JSON parser to use to replace an existing project that I originally wrote in Ruby.

## Current Status

Building a JSON parser is going to have a good number of pieces, and I'm also learning the language, so I want to have a way to have automated regression tests. I started with a simple `assertEqual`, but rapidly realized that there are complications with comparing and displaying lists, so I'm currently in the process of building the needed utilities around a usable `assertEqual`.

And, of course, once we can write effective tests, we'll want an easy way to run the tests. So, going to write a a tool to load up and run tests.

You can follow along by [https://coreyhaines.substack.com/](subscribing to the newsletter)!

