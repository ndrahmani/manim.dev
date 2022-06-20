---
layout: page
title: "Do you need Manim?"
---

Before hiring a developer, make sure that Manim is the right tool for what you are trying to produce:

<div class="alert" markdown="0">Manim is most suited for cases where you can animate something mathematical more efficiently by <u>writing a program</u>, instead of doing it manually by clicking around.</div>

We created a chart that can help you to decide:

{:refdef: style="text-align: center;"}
![Manim decision flowchart](/assets/img/manim_flowchart.svg)
{: refdef}

## Grant's advice

This flowchart is based on Grant's own advice:

{% include youtube_vid.html id="ruUfqQPDdDs?start=138" width="480px" height="270px" %}

You can also read it below:

> Step one is, make sure that what you're animating should be done so programmatically—because a lot of things maybe shouldn't. If you're just making a quick graph of something—if it's a graphical intuition that maybe has a little motion to it—use [Desmos](https://www.desmos.com/), [Grapher](https://en.wikipedia.org/wiki/Grapher), [Geogebra](https://www.geogebra.org/), [Mathematica](https://www.wolfram.com/mathematica/), certain things that are really oriented around graphs.
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