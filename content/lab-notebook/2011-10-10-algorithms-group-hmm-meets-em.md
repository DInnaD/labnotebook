---
categories:
- computation
comments: true
date: 2011-10-10T18:42:03Z
redirects:
- /wordpress/archives/2853
- /archives/2853
slug: algorithms-group-hmm-meets-em
tags:
- algorithms
title: Algorithms Group, HMM meets EM
url: /2011/10/10/algorithms-group-hmm-meets-em/
---

Alisa reviews [HMM](http://www.carlboettiger.info/archives/2521), [EM](http://www.carlboettiger.info/archives/2215), and shows us how to combine them.

The EM version treats the transition probabilities (exchanging coins) and emission probabilities (chance of heads/tails under each coin) as unknowns.  Make a guess, calculate the blue line from [before](http://www.carlboettiger.info/archives/2521).  This can be used to calculate a new guess that will hill climb to the locally optimum solution (EM).

New guess for the transition probability is:

$$ A_{lk} = \frac{f_i b_i a_{lk} e_k(x_{i+1}) }{P(x)} $$

New guess for the emission probability is just:

$$ \frac{\sum f_i b_i}{P(x)}$$

(example code coming)

Future Topics



	
  * Sweave/literate programming, Github -- Carl

	
  * Large Scale spatial analysis -- Yaniv

	
  * Bayesian CP analysis -- Alisa

	
  * Dirchelet process

	
  * machine learning: GA/SVM/NN -- Dave

	
  * Optimal Control/Lagrangian

	
  * EC2 / HPC

	
  * debug/profile/unit tests/code optimization


