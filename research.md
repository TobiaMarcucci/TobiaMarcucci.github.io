---
layout: page
title: "Research"
permalink: "/research"
---

My research sits at the intersection of convex and combinatorial optimization, with applications to robotics, motion planning, and optimal control.
Specifically, I study optimal decision making in circumstances where discrete and continuous choices have to be made simultaneously.
I work on these problems on a mathematical and numerical level: I develop modeling frameworks, transcriptions as numerical optimizations, and solution algorithms.
The questions at the core of my research are also central in machine learning and AI: foundation and large-language models have recently unlocked unprecedented opportunities for providing our robots with common sense and long-term reasoning, but have also highlighted the lack of optimization methods that can reliably and automatically generate large amounts of high-quality training data.

The main outcome of my PhD has been [Graphs of Convex Sets (GCS)](http://groups.csail.mit.edu/robotics-center/public_papers/Marcucci24a.pdf): a modelling and decision-making framework that efficiently combines graph search and convex optimization.
Formally, a GCS is a graph where each vertex is paired with a convex program, and each edge couples two programs through additional convex costs and constraints.
Any optimization problem over an ordinary weighted graph can be extended to GCS in a natural way, yielding a new class of problems with a wide range of applications.
My main contribution has been a general methodology to formulate any GCS problem as a lightweight mixed-integer program with tight convex relaxation.

The [shortest-path problem in GCS](https://arxiv.org/pdf/2101.11565) is especially important in control and robotics, since it encompasses as special cases many trajectory-optimization and motion-planning problems.
Through a single convex program, we can now design [globally optimal trajectories for a car traversing a maze in minimum time, or solve intricate bi-manual manipulation problems](https://www.science.org/stoken/author-tokens/ST-1559/full).

<!-- [Our laboratory](http://groups.csail.mit.edu/locomotion/) is mainly focused on robotics.
We use cutting-edge numerical optimization to solve manipulation and locomotion problems.
Never before has robotics posed such challenging and stimulating issues: our ambitious goal is to solve them using rigorous mathematics. -->
