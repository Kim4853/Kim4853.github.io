---
layout: default
title: Columns
permalink: /columns/
---

# Thoughts on AI and Academic Research

*September 2026* (modified)

I am a Ph.D. student in mechanical engineering, with research interests in machine learning, computational science, and applied mathematics. AI is both closely related to my field and deeply integrated into how I work.

Over the past year, I have used AI to read papers, examine mathematical arguments, develop numerical methods, write and debug code, analyze results, and explore new ideas. More importantly, it has changed how quickly I can move from an idea to an implementation, examine the result, and decide what to try next.

Discussions about AI in academia often fall into two extremes. Some expect it to replace much of what researchers do, while others consider it too unreliable to play a serious role in science. I am not confident in either view. The technology is changing too quickly to predict what research will look like five or ten years from now.

What is easier to discuss is what is already changing.

---

## AI is lowering the cost of exploration

Many research tasks that once required substantial time can now be attempted much more quickly.

AI can help a researcher understand an unfamiliar method, inspect existing code, produce an initial implementation, work through a derivation, or compare several approaches. More capable systems can modify and run programs, inspect outputs, and iterate on the results.

None of this means that the output is necessarily correct. AI can invent references, make mathematical mistakes, introduce subtle bugs, and confidently explain incorrect statements. But producing a first attempt has become much cheaper.

This matters because research is fundamentally exploratory. Instead of spending a week implementing one idea, it may become possible to examine several alternatives before deciding which deserves serious attention.

The same applies to writing and programming. As producing reasonable prose and functional code becomes easier, the ability to produce everything from scratch may become relatively less important. Understanding what has been produced, and deciding whether it is useful, becomes more important.

There is also a broader consequence. If producing research becomes cheaper while evaluating it remains expensive, academic publishing will face increasing pressure. More results can be generated and submitted, but the time available to examine them does not increase at the same rate.

---

## Verification may become the real bottleneck

In my own work, I increasingly spend less time producing everything from the beginning and more time deciding whether a result is correct, useful, and worth pursuing.

AI can generate a plausible mathematical argument very quickly. Someone still has to examine the assumptions, identify gaps, search for counterexamples, and determine whether the result actually matters.

The same problem appears in numerical research. A convincing result may represent real physics, but it may also come from grid resolution, numerical diffusion, boundary conditions, data leakage, optimization choices, or some other artifact.

For now, I find three questions particularly important:

**Why is this true?**

**How do we know this is not an artifact?**

**Why is this scientifically important?**

This is why I do not think technical knowledge becomes unnecessary as AI improves. Mathematical knowledge is needed to recognize a questionable argument. Numerical analysis is needed to understand suspicious computational behavior. Knowledge of the literature and physics is needed to determine whether a result is new or meaningful.

At the same time, mistakes are not unique to AI. Published research also contains mathematical errors, software bugs, statistical problems, and conclusions that exceed the evidence.

For this reason, I find the distinction between "human-generated" and "AI-generated" less useful than the distinction between **verifiable and unverifiable claims**.

The relevant question is not who produced a result, but whether the result survives independent examination.

---

## The human-AI division of labor will probably keep changing

A common argument is that humans will remain necessary because someone has to verify what AI produces.

For now, I largely agree. I use AI extensively, but I still consider myself responsible for understanding and checking the results that enter my work.

I am less certain that this is a permanent answer.

There is no obvious reason why AI should improve at producing results while making little progress at checking them. Future systems may generate an argument, test it with formal tools, implement an algorithm, run numerical experiments, compare alternative methods, and use other systems to independently criticize the result.

If that happens, researchers may increasingly supervise a collection of computational tools rather than personally reconstruct every step.

This would create new problems. How much evidence is sufficient? What happens when independent systems disagree? Who is responsible for a scientific claim when no individual has reproduced every part of the analysis?

Eventually, the amount and complexity of machine-generated research may even exceed what an individual researcher can directly inspect. At that point, verification itself becomes a problem of scientific infrastructure.

I therefore hesitate to define any particular task as permanently human. The boundary is already moving, and it will probably move again.

---

## There are too many unsolved problems to ignore useful help

This is ultimately why I find the debate over whether researchers "should" use AI somewhat narrow.

There is still an enormous amount that we do not know how to compute, predict, or design.

Turbulence remains difficult to predict across realistic regimes. Connecting molecular behavior to continuum models remains a major challenge. Large multiphysics simulations are often prohibitively expensive. Semiconductor manufacturing involves coupled processes across scales that are difficult to model and control. Nuclear reactors and fusion systems require reliable prediction under extreme conditions. Predicting degradation and remaining life in aircraft engines remains difficult. Space systems increasingly require autonomous decisions under limited observations. Many problems in climate, energy, materials, and engineering remain beyond what we can fully resolve with existing computational resources.

These problems are not waiting for researchers because we lack things to work on. In many cases, we are limited by computational cost, incomplete models, sparse observations, uncertainty, fragmented knowledge, and the finite amount of time and expertise available to humans.

No individual researcher can read every relevant paper, master every neighboring field, implement every method, explore every hypothesis, or run every possible computational experiment.

If AI can help overcome some of these limitations, I think we need that help.

The important possibility is not that AI can write a paragraph or generate code faster. It is that AI may allow researchers to explore problems that were previously too expensive, too complicated, too interdisciplinary, or simply too time-consuming. It may help connect mathematical ideas with physical models, numerical algorithms, software, experiments, and knowledge developed in different fields.

I understand why this can be uncomfortable. Researchers spend years developing the ability to derive equations, write code, understand difficult papers, and solve problems independently. When AI begins to perform some of these tasks, it can feel as though part of that expertise is being devalued.

But preserving our intellectual territory is not the purpose of science.

If AI can complete in an hour something that would otherwise take me a week, I can spend that week asking a harder question. If it can help me understand a method outside my field, I can test whether that method is useful for a problem I would otherwise never attempt. If it can connect ideas that I would not have connected myself, then the space of problems I can explore becomes larger.

Of course, that help must be treated critically. AI can be wrong, and researchers remain responsible for the claims they make. Mathematics, numerical analysis, physical understanding, and scientific judgment remain essential for deciding what to trust and what is worth pursuing.

But I would rather treat the limitations of AI as problems to be studied and managed than use them as reasons to reject the technology.

There are too many important problems left unsolved.

If that requires giving up some pride about what researchers are supposed to do entirely by themselves, I think that is a reasonable price to pay.