+++
date = "2016-11-29T09:36:51+02:00"
title = "Casey Muratori on 'clean' code"

+++

> And so, to the point that we care about how clean code is, we only care about
> that in so far as it has an affect on our end product.
>
> -- <cite>Casey Muratori</cite>

I used to care deeply about writing code that was as clean and elegant as
possible. Functions should be short, and do one thing only. Don't repeat
yourself. Don't have functions take more than three parameters. Functional
programming has some rather elegant abstractions around manipulating lists of
things too, and it was easy to feel proud of expressing a complex
transformation, in a few lines of careful crafted maps, filters, and reduces.
Yet somewhere is the background of my perceived 'clean code' lies the actual
problem I am trying to solve, buried under layers and layers of 'beautiful'
code.

> If the way you look at code is that you think of it as messy or clean, that is a
> very bad habit in my opinion.
>
> -- <cite>Casey Muratori</cite>

Enter Casey Muratori (of [Handmade Hero](https://handmadehero.org/) fame) and his
paradigm-shifting [rant](https://youtu.be/Lzc3HcIgXis?t=1768) on why seeing
code as messy or clean is a really bad habit. [^1] His perspective was different and
refreshing, and reminded me that code is merely a tool that we use to solve
problems, and that our job is to solve those problems, not write 'clean' code.
I'd summarize his salient points as follows:

- Thinking about how to make code not messy, whatever that means to you, is time
  you could have used to write code to figure out how to structure your
  program. You spent time that should have been spent thinking about the
  problem, on thinking about the code. In other words, you have wasted time.
  
- The end goal is to have good working code, not clean code. if you have the
  ugliest code in the world, but it runs efficiently, and has no bugs, then it
  didn't matter right?

- There is no prescribed set of rules that govern what clean code looks like.
  Clean code is never about the code itself, it's only ever about the usage or
  debugging process, and how the code affects that, in other words it must have
  a practical purpose, not just some aesthetic goal.

- Code will naturally clean up over time, prematurely cleaning it is worse than
  wasting time, because it may lead you down wrong, time consuming paths. For
  example, segregating things too early, and then having to spend more time
  later tying them together again.

- Focus on the problem you want to solve, and once you have solved that problem
  then you can think about how to clean up the code. Again, the focus of
  cleaning the code is to increase code debug-ability, readability, reuse etc.

[^1]: I highly recommend watching the whole
    lecture
    [What Programming is Never About](https://www.youtube.com/watch?v=Lzc3HcIgXis),
    by Abner Coimbre. It's thanks to him that I actually heard Casey's opinion
    on clean code.
