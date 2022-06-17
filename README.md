# awesome-information-geometry

[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/nocotan/awesome-information-geometry/blob/main/LICENSE)

This repo is a collection of AWESOME things about information geometry, including papers, code, etc. Feel free to star and fork.

# Contents
- [awesome-information-geometry](#awesome-information-geometry)
- [Contents](#contents)
- [Books](#books)
- [Papers](#papers)
  - [Survey](#survey)
  - [Information Geometry for Neural Networks](#information-geometry-for-neural-networks)
  - [Information Geometry for Clustering](#information-geometry-for-clustering)
  - [Information Geometry for MCMC](#information-geometry-for-mcmc)
  - [Information Geometry for HMM](#information-geometry-for-hmm)
  - [Fisher Information Matrix](#fisher-information-matrix)
  - [Natural Gradient](#natural-gradients)
  - [alpha-Divergence](#alpha-divergence)
  - [Exponential and Mixture Families](#exponential-and-mixture-families)
  - [Inequalities](#inequalities)
- [Library](#library)
- [Lectures and Tutorials](#lectures-and-tutorials)
  - [PDF](#pdf)
  - [YouTube](#youtube)
- [Conferences](#conferences)
- [Workshops](#workshops)

# Books
- Differential Geometrical Foundations of Information Geometry ([WorldScientific, 2022](https://www.worldscientific.com/worldscibooks/10.1142/9268))
- Progress in Information Geometry ([Springer, 2021](https://link.springer.com/book/10.1007/978-3-030-65459-7))
- Computational Information Geometry ([Springer, 2017](https://link.springer.com/book/10.1007/978-3-319-47058-0))
- Information Geometry ([Springer, 2017](https://www.springer.com/journal/41884))
- Information Geometry and Population Genetics ([Springer, 2017](https://link.springer.com/book/10.1007/978-3-319-52045-2))
- Information Geometry and Its Applications ([Springer, 2016](https://link.springer.com/book/10.1007/978-4-431-55978-8))
- Matrix Information Geometry ([Springer, 2013](https://link.springer.com/book/10.1007/978-3-642-30232-9))
- Methods of Information Geometry ([American Mathematical Soc., 2000](https://bookstore.ams.org/mmono-191))

# Papers

## Survey
- Fields of Application of Information Geometry ([Information Geometry, 2017](https://link.springer.com/chapter/10.1007/978-3-319-56478-4_6))
- Information geometry in optimization, machine learning and statistical inference ([Front. Electr. Electron. Eng. China, 2010](https://link.springer.com/article/10.1007/s11460-010-0101-3))

## Information Geometry for Neural Networks
- Principles of Riemannian Geometry in Neural Networks ([NeurIPS, 2017](https://papers.nips.cc/paper/2017/hash/0ebcc77dc72360d0eb8e9504c78d38bd-Abstract.html))
- f-GANs in an Information Geometric Nutshell ([NeurIPS, 2017](https://papers.nips.cc/paper/2017/hash/2f2b265625d76a6704b08093c652fd79-Abstract.html))
- Geometrical Singularities in the Neuromanifold of Multilayer Perceptrons ([NeurIPS, 2001](https://papers.nips.cc/paper/2001/hash/65d2ea03425887a717c435081cfc5dbb-Abstract.html))
- Algebraic Information Geometry for Learning Machines with Singularities ([NeurIPS, 2000](https://papers.nips.cc/paper/2000/hash/f442d33fa06832082290ad8544a8da27-Abstract.html))
- Gradient systems in view of information geometry ([Physica D: Nonlinear Phenomena, 1995](https://www.sciencedirect.com/journal/physica-d-nonlinear-phenomena))
- Information geometry of the EM and em algorithms for neural networks ([Neural Networks, 1995](https://www.sciencedirect.com/science/article/abs/pii/0893608095000038))
- Information geometry of Boltzmann machines ([IEEE Trans. Neural Networks, 1992](https://ieeexplore.ieee.org/abstract/document/125867))

## Information Geometry for Clustering
- On Clustering Histograms with k-Means by Using Mixed α-Divergences ([Entropy, 2014](https://www.mdpi.com/1099-4300/16/6/3273))

## Information Geometry for MCMC
- Geometric Aspects of Data-Processing of Markov Chains ([Arxiv, 2022](https://arxiv.org/abs/2203.04575))
- Information Geometry of Reversible Markov Chains ([Information Geometry, 2021](https://link.springer.com/article/10.1007/s41884-021-00061-7))
- Geometry of Markov Chains, Finite State Machines, and Tree Models ([IEICE Tech. Rep., 2014](https://www.ieice.org/ken/paper/20140718BBPQ/eng/))
- Information geometry approach to parameter estimation in Markov chains ([ISIT, 2014](https://ieeexplore.ieee.org/abstract/document/6875001))

## Information Geometry for HMM
- Information geometry approach to parameter estimation in hidden Markov model ([Bernoulli, 2022](https://projecteuclid.org/journals/bernoulli/volume-28/issue-1/Information-geometry-approach-to-parameter-estimation-in-hidden-Markov-model/10.3150/21-BEJ1344.short))

## Fisher Information Matrix
- The Spectrum of the Fisher Information Matrix of a Single-Hidden-Layer Neural Network ([NeurIPS, 2018](https://papers.nips.cc/paper/2018/hash/18bb68e2b38e4a8ce7cf4f6b2625768c-Abstract.html))
- Evaluating neuronal codes for inference using Fisher information ([NeurIPS, 2010](https://papers.nips.cc/paper/2010/hash/08b255a5d42b89b0585260b6f2360bdd-Abstract.html))

## Natural Gradients
- Sinkhorn Natural Gradient for Generative Models ([NeurIPS, 2020](https://papers.nips.cc/paper/2020/hash/122e27d57ae8ecb37f3f1da67abb33cb-Abstract.html))
- An Improved Analysis of (Variance-Reduced) Policy Gradient and Natural Policy Gradient Methods ([NeurIPS, 2020](https://papers.nips.cc/paper/2020/hash/56577889b3c1cd083b6d7b32d32f99d5-Abstract.html))
- Natural Policy Gradient Primal-Dual Method for Constrained Markov Decision Processes ([NeurIPS, 2020](https://papers.nips.cc/paper/2020/hash/5f7695debd8cde8db5abcb9f161b49ea-Abstract.html))
- Understanding Approximate Fisher Information for Fast Convergence of Natural Gradient Descent in Wide Neural Networks ([NeurIPS, 2020](https://papers.nips.cc/paper/2020/hash/7b41bfa5085806dfa24b8c9de0ce567f-Abstract.html))
- Ngboost: Natural gradient boosting for probabilistic prediction ([ICML, 2020](http://proceedings.mlr.press/v119/duan20a.html?ref=https://githubhelp.com))
- Fast Convergence of Natural Gradient Descent for Over-Parameterized Neural Networks ([NeurIPS, 2019](https://papers.nips.cc/paper/2019/hash/1da546f25222c1ee710cf7e2f7a3ff0c-Abstract.html))
- Limitations of the empirical Fisher approximation for natural gradient descent ([NeurIPS, 2019](https://papers.nips.cc/paper/2019/hash/46a558d97954d0692411c861cf78ef79-Abstract.html))
- Online natural gradient as a Kalman filter ([Electron. J. Stat., 2018](https://projecteuclid.org/journals/electronic-journal-of-statistics/volume-12/issue-2/Online-natural-gradient-as-a-Kalman-filter/10.1214/18-EJS1468.full))
- Fast Approximate Natural Gradient Descent in a Kronecker Factored Eigenbasis ([NeurIPS, 2018](https://papers.nips.cc/paper/2018/hash/48000647b315f6f00f913caa757a70b3-Abstract.html))
- Exact natural gradient in deep linear networks and its application to the nonlinear case ([NeurIPS, 2018](https://papers.nips.cc/paper/2018/hash/7f018eb7b301a66658931cb8a93fd6e8-Abstract.html))
- SLANG: Fast Structured Covariance Approximations for Bayesian Deep Learning with Natural Gradient ([NeurIPS, 2018](https://papers.nips.cc/paper/2018/hash/d3157f2f0212a80a5d042c127522a2d5-Abstract.html))
- Projected Natural Actor-Critic ([NeurIPS, 2013](https://papers.nips.cc/paper/2013/hash/dd77279f7d325eec933f05b1672f6a1f-Abstract.html))
- Stochastic Gradient Riemannian Langevin Dynamics on the Probability Simplex ([NeurIPS, 2013](https://papers.nips.cc/paper/2013/hash/309928d4b100a5d75adff48a9bfc1ddb-Abstract.html))
- Natural Policy Gradient Methods with Parameter-based Exploration for Control Tasks ([NeurIPS, 2010](https://papers.nips.cc/paper/2010/hash/44c4c17332cace2124a1a836d9fc4b6f-Abstract.html))
- A Generalized Natural Actor-Critic Algorithm ([NeurIPS, 2009](https://papers.nips.cc/paper/2009/hash/acf4b89d3d503d8252c9c4ba75ddbf6d-Abstract.html))
- Stochastic search using the natural gradient ([ICML, 2009](https://dl.acm.org/doi/abs/10.1145/1553374.1553522?casa_token=fo1cfbAvRXUAAAAA:2AOY3ZmMcvl_qDx9hWVil95hF7P6QrjZu5VJWo-6EBWoYkMLqc0oa9qcl0Jy-I09BSSME-h1Q9_72g))
- Incremental Natural Actor-Critic Algorithms ([NeurIPS, 2007](https://papers.nips.cc/paper/2007/hash/6883966fd8f918a4aa29be29d2c386fb-Abstract.html))
- Topmoumoute Online Natural Gradient Algorithm ([NeurIPS, 2007](https://papers.nips.cc/paper/2007/hash/9f61408e3afb633e50cdf1b20de6f466-Abstract.html))
- Natural Actor-Critic for Road Traffic Optimisation ([NeurIPS, 2006](https://papers.nips.cc/paper/2006/hash/78bc62d08a9a0b9b0b9c0ad339ef82d3-Abstract.html))
- Rprop using the natural gradient ([Trends and Applications in Constructive Approximation, 2005](https://link.springer.com/chapter/10.1007/3-7643-7356-3_19))
- A Natural Policy Gradient ([NeurIPS, 2001](https://papers.nips.cc/paper/2001/hash/4b86abe48d358ecf194c56c69108433e-Abstract.html))
- Natural gradient descent for on-line learning ([PRL, 1998](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.81.5461))
- Natural gradient works efficiently in learning ([Neural computation, 1998](https://ieeexplore.ieee.org/abstract/document/6790500))

## alpha-Divergence
- Log-determinant divergences revisited: Alpha-beta and gamma log-det divergences ([Entropy, 2015](https://www.mdpi.com/1099-4300/17/5/2988))
- On the chi square and higher-order chi distances for approximating f-divergences ([IEEE Signal Processing Letters, 2013](https://ieeexplore.ieee.org/abstract/document/6654274))
- Generalized alpha-beta divergences and their application to robust nonnegative matrix factorization ([Entropy, 2011](https://www.mdpi.com/1099-4300/13/1/134))
- Families of alpha-beta-and gamma-divergences: Flexible and robust measures of similarities ([Entropy, 2010](https://www.mdpi.com/1099-4300/12/6/1532))
- Information geometry of divergence functions ([Bull. Pol. Acad. Sci. Tech. Sci., 2010](https://www.infona.pl/resource/bwmeta1.element.baztech-article-BPG8-0020-0019))
- $\alpha $-Divergence Is Unique, Belonging to Both $f$-Divergence and Bregman Divergence Classes ([IEEE Trans. Information Theory, 2009](https://ieeexplore.ieee.org/abstract/document/5290302))

## Exponential and Mixture Families
- Information geometry of positive measures and positive-definite matrices: decomposable dually flat structure ([Entropy, 2014](https://www.mdpi.com/1099-4300/16/4/2131))
- Geometry of deformed exponential families: Invariant, dually-flat and conformal geometries ([Physica A, 2012](https://www.sciencedirect.com/science/article/pii/S037843711200310X?casa_token=5QWUwzlQnr0AAAAA:bWGXoEe3_Tw7fi-1AMPgCW0o7dGx2ZAyof3A_mG3Mwqp00MmxDeiXA5rLq-vejdfboyLam-vYto))
- Geometry of q-Exponential Family of Probability Distributions ([Entropy, 2011](https://www.mdpi.com/1099-4300/13/6/1170))

## Inequalities
- Cramér-Rao lower bound and information geometry ([Connected at Infinity II., 2013](https://link.springer.com/chapter/10.1007/978-93-86279-56-9_2))

# Library
- [NNGeometry](https://github.com/tfjgeorge/nngeometry)
- [natural-gradients](https://github.com/wiseodd/natural-gradients)
- [InformationGeometry.jl](https://github.com/RafaelArutjunjan/InformationGeometry.jl)
- [geodesical_skew_divergence](https://github.com/nocotan/geodesical_skew_divergence)

# Lectures and Tutorials
## PDF
- An elementary introduction to information geometry ([Entropy, 2022](https://www.mdpi.com/1099-4300/22/10/1100))
- Divergence function, information monotonicity and information geometry ([WITMSE, 2009](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.331.9566&rep=rep1&type=pdf))

## YouTube
- Information Geometry and Its Applications: Survey by Shun-Ichi Amari ([YouTube](https://www.youtube.com/watch?v=2Uy6xCpvnj0))
- Information Geometry by Microsoft Research ([YouTube](https://www.youtube.com/watch?v=zmUMBLEHhZg))
- Nihat Ay : Information Geometric structures in Cognitive Systems Research ([YouTube](https://www.youtube.com/watch?v=m3QbaIdJ-xs&t=65s))
- Computational Information Geometry with Frank Nielsen ([YouTube](https://www.youtube.com/watch?v=X3cBhBA1nNw))
- Information Geometry and its Application by Melvin Leok
 ([YouTube](https://www.youtube.com/watch?v=FlyJJIQo-g4&list=PLHZhjPByiV3L94AeJ9FcK1yrnRDOt3Vit))
 
# Journals
- Information Geometry ([Journal home](https://www.springer.com/journal/41884))

# Conferences
- International Conference on Information Geometry for Data Science ([IG4DS](https://www.dsf.tuhh.de/index.php/ig4ds/))
 
# Workshops
- Deep Learning through Information Geometry ([at NeurIPS 2020](https://sites.google.com/view/dl-info-neurips20))
