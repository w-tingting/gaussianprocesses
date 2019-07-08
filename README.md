## Table of Content

* [Presenters](#presenters)
* [Abstract](#abstract)
* [Link to Slides](#link-to-slides)
* [Notebooks](#notebooks)
* [References](#references)


## Presenters


## Abstract

Since the celebrated book by Rasmussen and Williams, there have been a considerable amount of novel contributions that are allowing the applicability of Gaussian processes (GPs) to problems at an unprecedented scale and to new areas where uncertainty quantification is of fundamental importance. 
This tutorial will expose attendees to recent advances in GP research; describe the current challenges in modeling and inference with GPs; their relationship to neural networks and deep neural networks and stimulate the debate about the role of GP models in solving complex machine-learning tasks. 

## Link to Slides

* [Introduction](slides/introduction.pdf)
* [Definition of Gaussian Processes](slides/gaussian_processes.pdf)
* [Model Approximations](slides/model_approximations.pdf)
* [Inference](slides/inference.pdf)
* [Challenges](slides/challenges.pdf)
* [Theory and Code](slides/theory_code.pdf)




## Notebooks

[Notebook Sampling from GP prior](notebooks/gp-priors.ipynb)

[Notebook on GP Regression](notebooks/gp-inference.ipynb)


## References

<link rel="import" href="references/references.html">
### Bayesian Deep Nets and Deep Gaussian Processes



<li><p><a name="Matthews18"></a>

De, J.&nbsp;Hron, M.&nbsp;Rowland, R.&nbsp;E. Turner, and Z.&nbsp;Ghahramani.
 Gaussian Process Behaviour in Wide Deep Neural Networks.
 In <em>International Conference on Learning Representations</em>, 2018.
[&nbsp;<a href="bayesian_dnns_dgps_bib.html#Matthews18">bib</a>&nbsp;| 
<a href="https://openreview.net/forum?id=H1-nGgWC-">http</a>&nbsp;]
<blockquote><font size="-1">
Keywords: deep_learning
</font></blockquote>

</li></p>

<li><p><a name="Cutajar17"></a>

K.&nbsp;Cutajar, E.&nbsp;V. Bonilla, P.&nbsp;Michiardi, and M.&nbsp;Filippone.
 Random feature expansions for deep Gaussian processes.
 In D.&nbsp;Precup and Y.&nbsp;W. Teh, editors, <em>Proceedings of the 34th
  International Conference on Machine Learning</em>, volume&nbsp;70 of <em>Proceedings
  of Machine Learning Research</em>, pages 884--893, International Convention
  Centre, Sydney, Australia, Aug. 2017. PMLR.
[&nbsp;<a href="bayesian_dnns_dgps_bib.html#Cutajar17">bib</a>&nbsp;| 
<a href="http://proceedings.mlr.press/v70/cutajar17a/cutajar17a.pdf">pdf</a>&nbsp;| 
<a href="http://proceedings.mlr.press/v70/cutajar17a.html">.html</a>&nbsp;]
<blockquote><font size="-1">
The composition of multiple Gaussian Processes as a Deep Gaussian Process DGP enables a deep probabilistic nonparametric approach to flexibly tackle complex machine learning problems with sound quantification of uncertainty. Existing inference approaches for DGP models have limited scalability and are notoriously cumbersome to construct. In this work we introduce a novel formulation of DGPs based on random feature expansions that we train using stochastic variational inference. This yields a practical learning framework which significantly advances the state-of-the-art in inference for DGPs, and enables accurate quantification of uncertainty. We extensively showcase the scalability and performance of our proposal on several datasets with up to 8 million observations, and various DGP architectures with up to 30 hidden layers.
</font></blockquote>
<li><p><blockquote><font size="-1">
Keywords: deep_learning
</font></blockquote>

</li></p>

<li><p><a name="Gal16"></a>

Y.&nbsp;Gal and Z.&nbsp;Ghahramani.
 Dropout As a Bayesian Approximation: Representing Model Uncertainty
  in Deep Learning.
 In <em>Proceedings of the 33rd International Conference on
  International Conference on Machine Learning - Volume 48</em>, ICML'16, pages
  1050--1059. JMLR.org, 2016.
[&nbsp;<a href="bayesian_dnns_dgps_bib.html#Gal16">bib</a>&nbsp;| 
<a href="http://dl.acm.org/citation.cfm?id=3045390.3045502">http</a>&nbsp;]
<blockquote><font size="-1">
Keywords: deep_learning
</font></blockquote>

</li></p>

<li><p><a name="Duvenaud14"></a>

D.&nbsp;K. Duvenaud, O.&nbsp;Rippel, R.&nbsp;P. Adams, and Z.&nbsp;Ghahramani.
 Avoiding pathologies in very deep networks.
 In <em>Proceedings of the Seventeenth International Conference on
  Artificial Intelligence and Statistics, AISTATS 2014, Reykjavik, Iceland,
  April 22-25, 2014</em>, volume&nbsp;33 of <em>JMLR Workshop and Conference
  Proceedings</em>, pages 202--210. JMLR.org, 2014.
[&nbsp;<a href="bayesian_dnns_dgps_bib.html#Duvenaud14">bib</a>&nbsp;| 
<a href="http://jmlr.org/proceedings/papers/v33/duvenaud14.html">.html</a>&nbsp;]
<blockquote><font size="-1">
Keywords: deep_gps
</font></blockquote>

</li></p>

<li><p><a name="Neal96"></a>

R.&nbsp;M. Neal.
 <em>Bayesian Learning for Neural Networks (Lecture Notes in
  Statistics)</em>.
 Springer, 1 edition, Aug. 1996.
[&nbsp;<a href="bayesian_dnns_dgps_bib.html#Neal96">bib</a>&nbsp;| 
<a href="http://www.worldcat.org/isbn/0387947248">http</a>&nbsp;]
<blockquote><font size="-1">
Artificial "neural networks" are widely used as flexible models for
classification and regression applications, but questions remain about how the
power of these models can be safely exploited when training data is limited.
This book demonstrates how Bayesian methods allow complex neural network
models to be used without fear of the "overfitting" that can occur with
traditional training methods. Insight into the nature of these complex
Bayesian models is provided by a theoretical investigation of the priors over
functions that underlie them. A practical implementation of Bayesian neural
network learning using Markov chain Monte Carlo methods is also described, and
software for it is freely available over the Internet. Presupposing only basic
knowledge of probability and statistics, this book should be of interest to
researchers in statistics, engineering, and artificial intelligence.
</font></blockquote>
<li><p><blockquote><font size="-1">
Keywords: neural
</font></blockquote>

</li></p></ul>
