---
layout: essay
type: essay
title: There Are Smarter Ways To Code
date: 2021-09-01
labels:
  - Design Patterns
---

### In The Begining

Way back when I first started coding in highschool, I had no idea what design patterns were. In fact, the only thing I had at the time was hope, believing that whatever I wrote to solve my problem will eventually work. And maybe this hope did work from time to time. But seeing my actual code, like the one contained in my first project, it is obvious that there are better solutions that can produce easier to read code without compromising results.

As I learned more computer science concepts, I was able to understand much more complicated code like those involving pointers and function arguments. And with this knowledge, I was able to expose myself to other software and projects, seeing how they are built. One example is that of OpenGL. The developers seem to have chosen to build it like a state machine. To enact change, the user must use functions, which require passing a constant variable that represents an abstract identity, and passing something like an object that we may want to bind to it. After doing all that, then the things the user may want to do is now possible.

### Deliberate Designs

Everytime I look at these projects I ask myself, “Why is this code written in the way it is now?” Some of the choices in design often bewilder me. Even with the previous example, handling OpenGL’s state machine like design is difficult for me at least due to having to always rebind objects just to change things. But in most cases, developers deliberately choose certain designs for certain problems knowing the pros and cons to them.

After my experience with writing not so desirable and readable code, I understand how important it is to adhere to using design patterns. They are templates, with each one having their benefits and cons when solving a problem. Many other people have figured out these patterns in design and when it is applicable to use them. So why shouldn’t I model my solutions based on these templates? However, I should remind myself that these templates need to be used carefully, as each one is used for a specific purpose. 

Thinking about it, though nearly all code I have written and designs I have chosen are purely built using just intuition on the spot, which may or may not have been a good solution, I have unintentionally used design patterns in some projects before. For one example, if I remember correctly, when I was modding one game I chose to use a singleton design in one part of the project. I reasoned that due to the need to implement global variables to be read by many other objects. In addition, it is pretty easy to implement. Was this a good design choice? Maybe or maybe not. But the main thing is that I have used a design pattern deliberately by reasoning what will best solve the issue..

### My Growth From Experience

In software development, solutions to problems should be carefully built with the choices having purpose and good reasons behind them. This is what design patterns are for, cookie cutters that are given to us when we recognize what the problem is asking from us. And as I begin to tackle more difficult problems, I have to think smarter with my solutions or else deal with confusing and convoluted code. And hopefully, as I grow accustomed to software developing, I will be able to easily determine what designs I can go about to solve a problem.
