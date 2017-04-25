---
categories:
- ecology
comments: true
date: 2011-01-26T17:12:18Z
redirects:
- /wordpress/archives/850
- /archives/850
slug: mcelreath-a-bayesian-approach-to-hierarchical-modeling-using-r-to-build-our-own-estimator-from-scratch
tags:
- seminar
title: 'McElreath: A Bayesian approach to hierarchical modeling, using R to build
  our own estimator from scratch'
url: /2011/01/26/mcelreath-a-bayesian-approach-to-hierarchical-modeling-using-r-to-build-our-own-estimator-from-scratch/
---

CPB workshop continues, introduction to Bayesian inference.

![]( http://farm6.staticflickr.com/5177/5391045675_a98fe0fc33_o.jpg )


[McElreath](http://xcelab.net/rm/) discusses (slides):



	
  * Bayes Theorem


$$ P(\theta | D) = \frac{Pr(D|\theta) Pr(\theta )}{Pr(D)} $$

	
  * Philosophy of Priors, Uninformative Priors



	
  * Confidence intervals / credible intervals for free



	
  * Computing the posterior: Directly or by MCMC


Nice visual example of updating prior as we add data:

[gist id="797795"]

	
  * King Markov and the chain islands.



	
  * Evaluating: Burn in , autocorrelation.  Thinning (saves memory).

	
  * Metropolis2.R bad mixing.

	
  * Compare better and worse proposal mechanisms, motivates Gibbs Sampling: propose from the posterior, always accepted.


Richard's code:

[gist id="797782"]
