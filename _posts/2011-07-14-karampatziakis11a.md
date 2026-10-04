---
abstract: 'An importance weight quantifies the relative importance of one example
  over another, coming up in applications of boosting, asymmetric classification costs,
  reductions, and active learning. The standard approach for dealing with importance
  weights in gradient descent is via multiplication of the gradient. We first demonstrate
  the problems of this approach when importance weights are large, and argue in favor
  of more sophisticated ways for dealing with them. We then develop an approach which
  enjoys an invariance property: that updating twice with importance weight $h$ is
  equivalent to updating once with importance weight $2h$. For many important losses
  this has a closed form update which satisfies standard regret guarantees when all
  examples have $h=1$. We also briefly discuss two other reasonable approaches for
  handling large importance weights. Empirically, these approaches yield substantially
  superior prediction with similar computational performance while reducing the sensitivity
  of the algorithm to the exact setting of the learning rate. We apply these to online
  active learning yielding an extraordinarily fast active learning algorithm that
  works even in the presence of adversarial noise.'
title: Online Importance Weight Aware Updates
year: '2011'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: karampatziakis11a
month: 0
tex_title: Online Importance Weight Aware Updates
firstpage: 440
lastpage: 451
page: 440-451
order: 440
cycles: false
bibtex_author: Karampatziakis, Nikos and Langford, John
author:
- given: Nikos
  family: Karampatziakis
- given: John
  family: Langford
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
pdf: https://raw.githubusercontent.com/mlresearch/r9/main/assets/karampatziakis11a/karampatziakis11a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
