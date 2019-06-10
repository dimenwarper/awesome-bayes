# Awesome Bayes
List of resources for bayesian inference

## Books

* [Statistical Rethinking](https://xcelab.net/rm/statistical-rethinking/)
* [Bayesian Data Analysis](http://www.stat.columbia.edu/~gelman/book/)
* [Probability Theory: The Logic of Science](https://www.amazon.com/Probability-Theory-E-T-Jaynes/dp/0521592712/ref=as_li_ss_tl?ie=UTF8&qid=1462140419&sr=8-1&keywords=probability+theory+the+logic+science&linkCode=sl1&tag=counbaye09-20&linkId=c8a7186d02be8069fd78b71cce57b3c0)
* [The Bayesian Choice](https://www.amazon.com/Bayesian-Choice-Decision-Theoretic-Computational-Implementation/dp/0387715983)
* [Bayesian methods for hackers](http://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/)
* [Bayesian Analysis with Python](https://www.amazon.com/gp/product/1789341655/ref=dbs_a_def_rwt_bibl_vppi_i0) | [errata and extra material](https://github.com/aloctavodia/BAP)


## Software/packages

### General inference
* [BUGS](http://www.openbugs.net/w/FrontPage): Bayesian Inference Using Gibbs Sampling. Oldest of the Bayesian inference platforms, tried and tested. Has a Windows friendly version, WinBUGS. R, python and many other language bindings, GUIs and 
* [JAGS](http://mcmc-jags.sourceforge.net/): Just another Gibbs sampler, similar to BUGS - focused on cross-platform, usability. Also tried and tested. R and python bindings too.
* [Stan](https://mc-stan.org/): Full-featured Bayesian inference with R and python bindings. Based on Hamiltonian MC and NUTS. Current favorite of the community it seems with lots of examples, docs.
* [PyMC3](https://docs.pymc.io/): Probabilistic programming in Python/Theano. PyMC4 is in dev, will use Tensorflow as backend. Great API and interface, but hindered by Theano's deprecation. PYMC4 promises great things.
* [edward2/tfprobability](https://github.com/tensorflow/probability/tree/master/tensorflow_probability/python/edward2): Probabilistic programming in tensorflow. Scalable models, but little docs.
* [Zhusuan](https://zhusuan.readthedocs.io/en/latest/): Another probabilistic programming framework built on tensorflow.
* [Pyro](https://pyro.ai/): Probabilistic programming in Pytorch. Good docs, scalable models too.
* [LaplacesDemon](https://cran.r-project.org/web/packages/LaplacesDemon/index.html): Mysterious probabilistic programming package in R with a cult following.
* [WebPPL](http://webppl.org/): Probabilistic programming in the browser.
* [Turing.jl](https://github.com/TuringLang/Turing.jl): Probabilistic programming in Julia, by Zoubin Ghahramani's lab.

### Specific
* [brms](https://github.com/paul-buerkner/brms) : Generalized linear/non-linear multilevel models, uses Stan.
* [R-INLA](http://www.r-inla.org/) : Latent Gaussian models via Integrated Nested Latent Approximations. Really fast compared to MCMC.
* [bayesmix](https://cran.r-project.org/web/packages/bayesmix/index.html): Finite mixture models with JAGS in R
* [lmm](https://cran.r-project.org/web/packages/lmm/index.html): Linear mixed models fitted with MCMC

### Misc
* [List of Bayesian inference packages for R](https://cran.r-project.org/web/views/Bayesian.html): Comprehensive list for all Bayesian inference in R
* [ArviZ](https://arviz-devs.github.io/arviz/): ArviZ is a Python package for exploratory analysis of Bayesian models. Includes functions for posterior analysis, sample diagnostics, model checking, and comparison. Works with PyMC3, PyStan, emcee, Pyro and TensorFlow Probability.
* [StatSim](https://statsim.com/): Browser-based interface to create, share, and perform inference on probabilistic models. Powered by WebPPL and PyMC3.

## Resources, papers, and blogs

### General topics
* [Michael Clark's Blog on Stat modeling, Bayesian inference](https://m-clark.github.io/documents.html)
* [Bayesian Spectacles](https://www.bayesianspectacles.org/)


### Introductory
* [Count Bayesie](https://www.countbayesie.com/all-posts): Will Kurt from "Get Programming with Haskell" fame explains basic probability and stats concepts through a Bayesian lens in a fun way. 
* [How to become a Bayesian in eight easy steps](https://link.springer.com/article/10.3758/s13423-017-1317-5)
* [Introduction to Bayesian Statistics](https://www.stat.auckland.ac.nz/~brewer/stats331.pdf): Course lectures by Brendon Brewer (University of Auckland)
* [Michael Jordan's Bayesian Statistics Course Notes](https://people.eecs.berkeley.edu/~jordan/courses/260-spring10/lectures/index.html)

### MCMC
* [The MCMC interactive gallery](https://chi-feng.github.io/mcmc-demo/): Build intuition for common MCMC routines using interactive demos. A walkthrough of the demos can be found [here](http://elevanth.org/blog/2017/11/28/build-a-better-markov-chain/).
* [The MCMC handbook intro to MCMC](https://www.mcmchandbook.net/HandbookChapter1.pdf): A no-frills intro to MCMC
* [Scaling up Bayesian inference](https://simons.berkeley.edu/sites/default/files/docs/6625/dunsonsimons2017.pdf): For Big Data™

### Variational Inference
* [Intro to variational inference via mean field approx](https://blog.evjang.com/2016/08/variational-bayes.html)
* [David Blei's Variational Inference tutorial](https://www.cs.princeton.edu/courses/archive/fall11/cos597C/lectures/variational-inference-i.pdf)
* [Expectation Maximization and Variational Inference](https://chrischoy.github.io/research/Expectation-Maximization-and-Variational-Inference/) 

### Empirical Bayes
* [Understanding Empirical Bayes](http://varianceexplained.org/r/empirical_bayes_baseball/)
* [Efron's overview of Empirical Bayes](http://statweb.stanford.edu/~ckirby/brad/papers/2013EBModeling.pdf)

### Non-parametrics
* [Collection of tutorials on non-parametrics](http://stat.columbia.edu/~porbanz/npb-tutorial.html)
* [Infinite mixture models](https://blog.echen.me/2012/03/20/infinite-mixture-models-with-nonparametric-bayes-and-the-dirichlet-process/)
* [A Visual Exploration of Gaussian Processes](https://distill.pub/2019/visual-exploration-gaussian-processes/)

### INLA
* [A gentle INLA tutorial](https://www.precision-analytics.ca/blog-1/inla)
* [Step by step INLA tutorial](http://www.flutterbys.com.au/stats/tut/tut12.9.html)

### Bayesian deep learning
* [Yarin Gal's talk on Bayesian Deep Learning](https://www.cs.ox.ac.uk/people/yarin.gal/website/PDFs/2017_OReilly_talk.pdf): Blog post of the talk is also very informative, check it out [here](http://mlg.eng.cam.ac.uk/yarin/blog_3d801aa532c1ce.html)
* [What is a variational autoencoder?](https://jaan.io/what-is-variational-autoencoder-vae-tutorial/)

### Misc
* [Probabilistic Numerics](http://probabilistic-numerics.org/): View all numeric optimization through a Bayesian lens

### Michael Betancourt's case studies

Indexed [here](https://betanalpha.github.io/writing/), these deserve a list all to themselves:
* [Principled Bayesian Worflow](https://betanalpha.github.io/assets/case_studies/principled_bayesian_workflow.html): What to know and what to look for when doing Bayesian inference.
* [Conceptual introduction to Hamiltonian MC](https://arxiv.org/pdf/1701.02434.pdf)
* [Identifying Bayesian Mixture Models](https://betanalpha.github.io/assets/case_studies/identifying_mixture_models.html)
* [Diagnosing Biased Inference Using Divergences](https://betanalpha.github.io/assets/case_studies/divergences_and_bias.html)


## People

* [Michael Jordan](https://people.eecs.berkeley.edu/~jordan/)
* [Zoubin Ghahramani](http://mlg.eng.cam.ac.uk/zoubin/)
* [Danielle Navarro](https://compcogscisydney.org/)
* [Michael Betancourt](https://betanalpha.github.io/)
* [Dan Simpson](https://twitter.com/dan_p_simpson?lang=en)
* [Thomas Wiecki](https://www.patreon.com/twiecki)
* [David Blei](http://www.cs.columbia.edu/~blei/)
* [Andrew Gelman](http://www.stat.columbia.edu/~gelman/)
* [Dustin Tran](http://dustintran.com/)
* [Yarin Gal](http://www.cs.ox.ac.uk/people/yarin.gal/website/)

