---
layout: page
title:  "About"
---

𝚖𝚊𝚗𝚒𝚖.𝚍𝚎𝚟 is a roster and job board for hiring Manim developers. Our goal is to collect useful information in one place and improve the discoverability of developers.

## About Manim

Manim is an community maintained Python library for creating mathematical animations. It was created in 2015 by Grant Sanderson, a.k.a. 3blue1brown, as a personal project to produce his own videos. As his channel gained popularity, many grew to like the style of his animations and wanted to use Manim for their own projects. However, as Manim was only intended for personal use, it was very difficult for other users to install and use it.

Manim has since been adopted by a group of developers, who forked it mid-2020 into what is now known as the [community edition](https://manim.community). Grant on the other hand still continues to produce videos using [his original branch](https://3b1b.github.io/manim/), having added OpenGL support. There are ongoing efforts in the Manim Community to reconcile these changes into the community edition. Check out [this webpage](https://docs.manim.community/en/stable/installation/versions.html) for more information on the different versions of Manim currently under development.

## When your should use Manim

Manim is most suited for cases where you can animate something more **efficiently by writing a program for it**, instead of doing it manually. Grant Sanderson [gives the following advice](https://youtu.be/ruUfqQPDdDs?t=138):

> Step one is, make sure that what you're animating should be done so, programmatically—because a lot of things maybe shouldn't. If you're just making a quick graph of something—if it's a graphical intuition that maybe has a little motion to it—use [Desmos](https://www.desmos.com/), [Grapher](https://en.wikipedia.org/wiki/Grapher), [Geogebra](https://www.geogebra.org/), [Mathematica](https://www.wolfram.com/mathematica/), certain things that are really oriented around graphs.
>
> The original thought I had in making Manim was that there are so many different ways of representing functions—other than graphs—in particular things like transformations. For example, use movement over time to communicate relationships between inputs and outputs instead of x and y directions, or vector fields, or things like that.
>
> I wanted something that was flexible enough that you didn't feel constrained into a graphical environment—by graphical I mean graphs with x and y coordinates. But also make sure that you're taking advantage of the fact that it's programmatic. You have loops, conditionals, abstraction. If any of those are well fit for what you want to teach, to have
>
> - a scene type that you tweak a little bit based on parameters,
> - conditionals so that things can go one way or another,
> - loops so that you can create things of arbitrarily increasing complexity,
>
> that's the stuff that's meant to be animated programmatically. **If it's just writing some text on the screen or shifting around objects or something like that, you should probably just use [Keynote](https://www.apple.com/keynote)—it will be a lot simpler.**
>
> Try to find a workflow that distills down that which should be programmatic into Manim, and that which doesn't need to be
> into other domains.