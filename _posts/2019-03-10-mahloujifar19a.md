---
title: Can Adversarially Robust Learning LeverageComputational Hardness?
abstract: "Making learners robust to adversarial perturbation at test time (i.e.,
  evasion attacks finding adversarial examples) or training time (i.e., data poisoning
  attacks) has emerged as a challenging task. It is known that in some cases \\emph{sublinear}
  perturbations in the  training phase or the testing phase can drastically decrease
  the quality of the predictions. These negative results, however,  only prove the
  \\emph{existence} of such successful adversarial perturbations. A natural question
  for these settings is whether or not we can make classifiers \\emph{computationally}
  robust to \\emph{polynomial-time} attacks.\r In this work, we prove some barriers
  against achieving such envisioned computational robustness  for evasion attacks
  (for specific metric probability spaces) as well as  poisoning attacks. In particular,
  \ we show that if the test instances come from a product distribution (e.g., uniform
  over $\\{0,1\\}^n$ or $[0,1]^n$, or isotropic $n$-variate Gaussian) and that  there
  is an initial constant error, then there exists a \\emph{polynomial-time} attack
  that finds adversarial examples of Hamming distance $O(\\sqrt n)$. \r For poisoning
  attacks, we prove that for any  deterministic learning algorithm with sample complexity
  $m$ and any efficiently computable “predicate” defining some “bad” property $B$
  for the produced hypothesis (e.g., failing on a particular test) that happens with
  an initial constant probability, there  exist a \\emph{polynomial-time} online poisoning
  attack that replaces  $O (\\sqrt m)$ of the training examples with other correctly
  labeled examples and increases the probability of the bad event $B$ to  $\\approx
  1$. \r Both of our poisoning and  evasion attacks are   \\emph{black-box} in how
  they access  their corresponding components of the system (i.e., the hypothesis,
  the concept, and the learning algorithm)."
layout: inproceedings
series: Proceedings of Machine Learning Research
id: mahloujifar19a
month: 0
tex_title: Can Adversarially Robust Learning LeverageComputational Hardness?
firstpage: 581
lastpage: 609
page: 581-609
order: 581
cycles: false
bibtex_author: Mahloujifar, Saeed and Mahmoody, Mohammad
author:
- given: Saeed
  family: Mahloujifar
- given: Mohammad
  family: Mahmoody
date: 2019-03-10
address: 
publisher: PMLR
container-title: Proceedings of the 30th International Conference on Algorithmic Learning
  Theory
volume: '98'
genre: inproceedings
issued:
  date-parts:
  - 2019
  - 3
  - 10
pdf: http://proceedings.mlr.press/v98/mahloujifar19a/mahloujifar19a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
