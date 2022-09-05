---
title: "Metric Spaces"
date: 2022-09-08
draft: false
---

Let `$(X, d)$` be a metric space. Define a function `$\bar{d}: X \times X \to \R$` by `$\bar{d}(p, q) = \min(d(p, q), 1)$`. Recall that the metric space `$(X, d)$` is said to be bounded if there exits `$M\in \R$` such that for all points `$p, q\in X$` we have `$d(p, q) < M$` 

1. Show that `$\bar{d}$` is a metric on `$X$`.
2. __Prove or disprove:__  The metrics `$d$` and `$\bar{d}$` induce the same topology on `$X$`.
3. __Prove or disprove:__  The metrics `$d$` and `$\bar{d}$` are Lipschitz equivalent if and only if `$(X, d)$` is bounded.
