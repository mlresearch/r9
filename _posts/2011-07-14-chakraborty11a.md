---
abstract: 'We study learning in a noisy bisection model: specifically, Bayesian algorithms
  to learn a target value V given access only to noisy realizations of whether V is
  less than or greater than a threshold theta. At step t = 0, 1, 2, ..., the learner
  sets threshold theta t and observes a noisy realization of sign(V - theta t). After
  T steps, the goal is to output an estimate V^ which is within an eta-tolerance of
  V . This problem has been studied, predominantly in environments with a fixed error
  probability q < 1/2 for the noisy realization of sign(V - theta t). In practice,
  it is often the case that q can approach 1/2, especially as theta -> V, and there
  is little known when this happens. We give a pseudo-Bayesian algorithm which provably
  converges to V. When the true prior matches our algorithm’s Gaussian prior, we show
  near-optimal expected performance. Our methods extend to the general multiple-threshold
  setting where the observation noisily indicates which of k >= 2 regions V belongs
  to.'
title: Near-Optimal Target Learning With Stochastic Binary Signals
year: '2011'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chakraborty11a
month: 0
tex_title: Near-Optimal Target Learning With Stochastic Binary Signals
firstpage: 97
lastpage: 104
page: 97-104
order: 97
cycles: false
bibtex_author: Chakraborty, Mithun and Das, Sanmay and Magdon-Ismail, Malik
author:
- given: Mithun
  family: Chakraborty
- given: Sanmay
  family: Das
- given: Malik
  family: Magdon-Ismail
date: 2011-07-14
note: Reissued by PMLR on 04 October 2026.
address:
container-title: Proceedings of the 27th Conference on Uncertainty in Artificial Intelligence
volume: R9
genre: inproceedings
issued:
  date-parts:
  - 2011
  - 7
  - 14
pdf: https://raw.githubusercontent.com/mlresearch/r9/main/assets/chakraborty11a/chakraborty11a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
