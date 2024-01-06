---
layout: post
title:  "Notes example"
date:   2023-xx-xx 21:21:21 +0530
tags: [stochastic]
---
> This at UCLA.
  
In following property:

$$
\langle F(t) \rangle = 0, \quad \langle F(t) F(t') \rangle = 2B \delta (t- t').
$$

For general stochastic differential equations in math community, such notations are not used. Instead, one uses the abstract symbol $\mathrm{d}W_t$, where $W_t$ represents a Wiener process, also known as the standard Brownian motion. $W_t$ is defined by the following properties:
- The trajectory of $W_t$ is continuous with probability 1.
- For given $t$, $W_t \sim \mathcal{N}(0,t)$, i.e., $W_t$ follows a Gaussian distribution with mean 0, variance $t$ (1d version).
- For any countable set ${t_0,...,t_n}$ with $t_0 < t_1 < \cdots < t_n$, $\{W_{t_i}-W_{t_{i-1}}: i\in \{ 1 ,..., N\}\}$ are independent of each other.

### Implications of $\langle F(t)F(t') \rangle= 2B \delta(t-t')$
Suppose that

$$
X_t = X_0 + \int_0^t Y_t F_t \mathrm{d} t.
$$

Consider the $N \rightarrow +\infty$ limit of the following averaged sum:

