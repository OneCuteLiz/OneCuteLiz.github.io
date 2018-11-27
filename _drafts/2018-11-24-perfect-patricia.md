---
layout: post
title:  "Perfect Patricia"
date:   2018-11-24
---

#### The Right Way
I wanted to do my first Ruby on Rails app the "right way" - using Test Driven Design (TDD).  
In the most simplest of explanations:  with TDD, you build tests first, write code to pass your tests, see if there is an opportunity to make your code better, then repeat.  The longer and more official explanation can be found [here](https://blog.makersacademy.com/an-introduction-to-tdd-in-ruby-72f0a8536509). 

I was sold on how a well written test can help you:
* build only the pieces you need, as you need them
* understand _the_ change that broke the thing (for the most part)
* remind you to better your code as you go along

Armed with conviction, gumption and some knowledge per this excellent book [__Practical Object-Oriented Design__](https://www.poodr.com/) I was ready.

Until I wasn't. 
I was stumpted.

How did I know what classes I actually needed? 
In all the videos I watched, those coding the tests just seemed to just _KNOW_ what classes and methods their super-simplistic-example-app needed. 

How did I know what messages were needed?
And it seemed best practice to understand the messsages (the returns/yield of each method) sent within the application. 

OH! Ha, one other thing: tests are written using RSpec...
It's Ruby, but looks like it isn't when you've never done it before with it's assertions. 



