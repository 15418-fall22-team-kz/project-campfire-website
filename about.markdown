---
layout: page
title: About
permalink: /about/
---

We implemented a two-dimensional chemical reaction simulator that can simulate a combination of concentration regions and particle regions in the same scene. Parallelizing this simulator with OpenMP, we were able to achieve a total speedup of 5.6 for a 200,000 particle simulation over 200 iterations on the 8-core Gates-Hillman Center (GHC) machines. The speedups and amount of cache misses for several sub-routines were examined to explain the less-than-perfect speedup. Additionally, we were able to achieve a total speedup of 22.23 for a 200,000 particle simulation over 200 iterations with 64 cores on the Pittsburgh Supercomputing Center (PSC) Bridges-2 machines. This work was complemented by the development of visualization software, allowing us to represent the iteration-by-iteration results of the simulations as a GIF.


[Github Repository]: https://github.com/jekyll
