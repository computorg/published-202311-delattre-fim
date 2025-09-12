# Computing an empirical Fisher information matrix estimate in latent variable models through stochastic approximation

[![build and publish](https://github.com/computorg/published-202311-delattre-fim/actions/workflows/build.yml/badge.svg)](https://github.com/computorg/published-202311-delattre-fim/actions/workflows/build.yml)
[![DOI:10.57750/r5gx-jk62](https://img.shields.io/badge/DOI-10.57750/r5gx--jk62-034E79.svg)](https://doi.org/10.57750/r5gx-jk62)
[![reviews](https://img.shields.io/badge/review-report-blue)](https://github.com/computorg/published-202311-delattre-fim/issues?q=is%3Aopen+is%3Aissue+label%3Areview)
[![SWH](https://archive.softwareheritage.org/badge/origin/https://github.com/computorg/published-202311-delattre-fim/)](https://archive.softwareheritage.org/browse/origin/?origin_url=https://github.com/computorg/published-202311-delattre-fim)
[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/80x15.png)](http://creativecommons.org/licenses/by/4.0/)

Authors: 

- Maud Delattre (Université Paris-Saclay, INRAE, MaIAGE, 78350, Jouy-en-Josas, France)
- Estelle Kuhn (Université Paris-Saclay, INRAE, MaIAGE, 78350, Jouy-en-Josas, France)

  The Fisher information matrix (FIM) is a key quantity in statistics. However its exact computation is often not trivial. In particular in many latent variable models, it is intricated due to the presence of unobserved variables. Several methods have been proposed to approximate the  FIM when it can not be evaluated analytically.  Different  estimates have been considered, in particular moment estimates. However some of them require to compute second derivatives of the complete data log-likelihood which leads to some disadvantages. In this paper, we focus on the empirical Fisher information matrix defined as an empirical estimate of the covariance matrix of the score, which only requires to compute the first derivatives of the log-likelihood. Our contribution consists in presenting a new numerical method to evaluate this empirical Fisher information matrix in latent variable model when the proposed estimate can not be directly analytically evaluated. We propose a stochastic approximation estimation algorithm to compute this estimate as a by-product of the parameter estimate. We evaluate the finite sample size properties of the proposed estimate and the convergence properties of the estimation algorithm through simulation studies. 