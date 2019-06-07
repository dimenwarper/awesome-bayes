# Awesome Bayes
List of resources for bayesian inference

## Books

* [Statistical Rethinking](https://xcelab.net/rm/statistical-rethinking/)
* [Bayesian Data Analysis](http://www.stat.columbia.edu/~gelman/book/)
* [Probability Theory: The Logic of Science](https://www.amazon.com/Probability-Theory-E-T-Jaynes/dp/0521592712/ref=as_li_ss_tl?ie=UTF8&qid=1462140419&sr=8-1&keywords=probability+theory+the+logic+science&linkCode=sl1&tag=counbaye09-20&linkId=c8a7186d02be8069fd78b71cce57b3c0)
* [Bayesian methods for hackers](http://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/)
* [Bayesian Analysis with Python](https://www.amazon.com/gp/product/1789341655/ref=dbs_a_def_rwt_bibl_vppi_i0)
* [Bayesian Statistics the Fun Way](https://nostarch.com/learnbayes)


## Packages

### General inference
* [BUGS](http://www.openbugs.net/w/FrontPage): Bayesian Inference Using Gibbs Sampling. Oldest of the Bayesian inference platforms, tried and tested. Has a Windows friendly version, WinBUGS. R, python and many other language bindings, GUIs and 
* [JAGS](http://mcmc-jags.sourceforge.net/): Just another Gibbs sampler, similar to BUGS - focused on cross-platform, usability. Also tried and tested. R and python bindings too.
* [Stan](https://mc-stan.org/): Full-featured Bayesian inference with R and python bindings. Based on Hamiltonian MC and NUTS. Current favorite of the community it seems with lots of examples, docs.
* [PyMC3](https://docs.pymc.io/): Probabilistic programming in Python/Theano. PyMC4 is in dev, will use Tensorflow as backend. Great API and interface, but hindered by Theano's deprecation. PYMC4 promises great things.
* [edward2/tfprobability](https://github.com/tensorflow/probability/tree/master/tensorflow_probability/python/edward2): Probabilistic programming in tensorflow. Scalable models, but little docs.
* [Pyro](https://pyro.ai/): Probabilistic programming in Pytorch. Good docs, scalable models too.
* [LaplacesDemon](https://cran.r-project.org/web/packages/LaplacesDemon/index.html): Mysterious probabilistic programming package in R with a cult following.

### Specific
* [brms](https://github.com/paul-buerkner/brms) : Generalized linear/non-linear multilevel models, uses Stan.
* [R-INLA](http://www.r-inla.org/) : Latent Gaussian models via Integrated Nested Latent Approximations. Really fast compared to MCMC.

### Misc
* [List of Bayesian inference packages for R](https://cran.r-project.org/web/views/Bayesian.html): Comprehensive list for all Bayesian inference in R


Diagnostics and visualization
* [ArviZ](https://arviz-devs.github.io/arviz/)
* Stan and PyMC have their own tools for model checking, viz, etc.

## Blogs and Tutorials

* [Michael Clark's Blog on Stat modeling, Bayesian inference](https://m-clark.github.io/documents.html)
* [The MCMC interactive gallery](https://chi-feng.github.io/mcmc-demo/): Build intuition for common MCMC routines using interactive demos. A walkthrough of the demos can be found [here](http://elevanth.org/blog/2017/11/28/build-a-better-markov-chain/).
* [Intro to variational inference via mean field approx](https://blog.evjang.com/2016/08/variational-bayes.html)
* [David Blei's Variational Inference tutorial](https://www.cs.princeton.edu/courses/archive/fall11/cos597C/lectures/variational-inference-i.pdf)
* [Understanding Empirical Bayes](http://varianceexplained.org/r/empirical_bayes_baseball/)

### Michael Betancourt's case studies

Indexed [here](https://betanalpha.github.io/writing/), these deserve a list all to themselves:
* [Principled Bayesian Worflow](https://betanalpha.github.io/assets/case_studies/principled_bayesian_workflow.html): What to know and what to look for when doing Bayesian inference.
* [Conceptual introduction to Hamiltonian MC](https://arxiv.org/pdf/1701.02434.pdf)
* [Identifying Bayesian Mixture Models](https://betanalpha.github.io/assets/case_studies/identifying_mixture_models.html)
* [Diagnosing Biased Inference Using Divergences](https://betanalpha.github.io/assets/case_studies/divergences_and_bias.html)


## People

* [Michael Jordan](https://people.eecs.berkeley.edu/~jordan/)
* [Danielle Navarro](https://compcogscisydney.org/)
* [Michael Betancourt](https://betanalpha.github.io/)
* [Dan Simpson](https://twitter.com/dan_p_simpson?lang=en)
* [Thomas Wiecki](https://www.patreon.com/twiecki)
* [David Blei](http://www.cs.columbia.edu/~blei/)
* [Andrew Gelman](http://www.stat.columbia.edu/~gelman/)
* [Dustin Tran](http://dustintran.com/)

