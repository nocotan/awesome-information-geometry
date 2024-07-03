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
  - [Information Geometry for NMF](#information-geometry-for-nmf)
  - [Information Geometry for MCMC](#information-geometry-for-mcmc)
  - [Information Geometry for HMM](#information-geometry-for-hmm)
  - [Information Geometry for Dimension Reduction](#information-geometry-for-dimension-reduction)
  - [Information Geometry and Optimization](#information-geometry-and-optimization)
  - [Fisher Information Matrix](#fisher-information-matrix)
  - [Fisher Kernels](#fisher-kernels)
  - [Information Diffusion Kernels](#information-diffusion-kernels)
  - [Natural Gradients](#natural-gradients)
  - [Statistical Manifolds and Hessian Information Geometry](#statistical-manifolds-and-hessian-information-geometry)
  - [alpha-Divergence](#alpha-divergence)
  - [Bregman Divergence](#bregman-divergence)
  - [Jensen-Shannon Divergence](#jensen-shannon-divergence)
  - [Exponential and Mixture Families](#exponential-and-mixture-families)
  - [Inequalities](#inequalities)
  - [Transport Information Geometry](#transport-information-geometry)
  - [Computational Information Geometry](#computational-information-geometry)
- [Library](#library)
- [Lectures and Tutorials](#lectures-and-tutorials)
  - [PDF](#pdf)
  - [YouTube](#youtube)
- [Journals](#journals)
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
- A Rate-Distortion View of Uncertainty Quantification ([ICML, 2024](https://arxiv.org/abs/2406.10775v2))
- Riemannian SAM: Sharpness-Aware Minimization on Riemannian Manifolds ([NeurIPS, 2023](https://openreview.net/forum?id=strvrjSi3C))
- The Geometry of Neural Nets' Parameter Spaces Under Reparametrization ([NeurIPS, 2023](https://openreview.net/forum?id=vtLNwa6uX0))
- Group Equivariant Sparse Coding ([GSI, 2023](https://link.springer.com/chapter/10.1007/978-3-031-38271-0_10))
- Can Generalised Divergences Help for Invariant Neural Networks? ([GSI, 2023](Can Generalised Divergences Help for Invariant Neural Networks?))
- Continuous Kendall Shape Variational Autoencoders ([GSI, 2023](https://link.springer.com/chapter/10.1007/978-3-031-38271-0_8))
- Functional Properties of PDE-Based Group Equivariant Convolutional Neural Networks ([GSI, 2023](https://link.springer.com/chapter/10.1007/978-3-031-38271-0_7))
- A Neurogeometric Stereo Model for Individuation of 3D Perceptual Units ([GSI, 2023](https://link.springer.com/chapter/10.1007/978-3-031-38271-0_6))
- Fisher-Legendre (FishLeg) optimization of deep neural networks  ([ICLR, 2023](https://openreview.net/forum?id=c9lAOPvQHS))
- The Fisher–Rao loss for learning under label noise ([Information Geometry, 2022](https://link.springer.com/article/10.1007/s41884-022-00076-8))
- A Reparametrization-Invariant Sharpness Measure Based on Information Geometry ([NeurIPS, 2022](https://nips.cc/Conferences/2022/Schedule?showEvent=53360))
- The Information Geometry of Unsupervised Reinforcement Learning ([ICLR, 2022](https://arxiv.org/abs/2110.02719))
- IGAGCN: Information geometry and attention-based spatiotemporal graph convolutional networks for traffic flow prediction ([Neural Networks, 2021](https://www.sciencedirect.com/science/article/abs/pii/S0893608021002318))
- Catastrophic Fisher Explosion: Early Phase Fisher Matrix Impacts Generalization ([ICML, 2021](http://proceedings.mlr.press/v139/jastrzebski21a.html))
- An Information-Geometric Distance on the Space of Tasks ([ICML, 2021](https://proceedings.mlr.press/v139/gao21a.html))
- Information Geometry of Orthogonal Initializations and Training ([ICLR, 2020](https://openreview.net/forum?id=rkg1ngrFPr))
- Fisher-rao metric, geometry, and complexity of neural networks ([AISTATS, 2019](https://proceedings.mlr.press/v89/liang19a.html))
- Principles of Riemannian Geometry in Neural Networks ([NeurIPS, 2017](https://papers.nips.cc/paper/2017/hash/0ebcc77dc72360d0eb8e9504c78d38bd-Abstract.html))
- f-GANs in an Information Geometric Nutshell ([NeurIPS, 2017](https://papers.nips.cc/paper/2017/hash/2f2b265625d76a6704b08093c652fd79-Abstract.html))
- Principal whitened gradient for information geometry ([Neural Networks, 2008](https://www.sciencedirect.com/science/article/abs/pii/S0893608007002523))
- Geometrical Singularities in the Neuromanifold of Multilayer Perceptrons ([NeurIPS, 2001](https://papers.nips.cc/paper/2001/hash/65d2ea03425887a717c435081cfc5dbb-Abstract.html))
- Algebraic Information Geometry for Learning Machines with Singularities ([NeurIPS, 2000](https://papers.nips.cc/paper/2000/hash/f442d33fa06832082290ad8544a8da27-Abstract.html))
- Gradient systems in view of information geometry ([Physica D: Nonlinear Phenomena, 1995](https://www.sciencedirect.com/journal/physica-d-nonlinear-phenomena))
- Information geometry of the EM and em algorithms for neural networks ([Neural Networks, 1995](https://www.sciencedirect.com/science/article/abs/pii/0893608095000038))
- Information geometry of Boltzmann machines ([IEEE Trans. Neural Networks, 1992](https://ieeexplore.ieee.org/abstract/document/125867))

## Information Geometry for Clustering
- A novel clustering algorithm based on information geometry for cooperative spectrum sensing ([IEEE Systems Journal, 2020](https://ieeexplore.ieee.org/abstract/document/9123433))
- On Clustering Histograms with k-Means by Using Mixed α-Divergences ([Entropy, 2014](https://www.mdpi.com/1099-4300/16/6/3273))
- Barycentric distribution estimation for texture clustering based on information-geometry tools ([ISETC, 2012](https://ieeexplore.ieee.org/abstract/document/6408132))

## Information Geometry for NMF
- Non-negative low-rank approximations for multi-dimensional arrays on statistical manifold ([Information Geometry, 2023](https://link.springer.com/article/10.1007/s41884-023-00100-5))
- Geometrical formulation of the nonnegative matrix factorization ([ICONIP, 2018](https://link.springer.com/chapter/10.1007/978-3-030-04182-3_46))
- Generalized alpha-beta divergences and their application to robust nonnegative matrix factorization ([Entropy, 2011](https://www.mdpi.com/1099-4300/13/1/134))

## Information Geometry for MCMC
- Geometric Aspects of Data-Processing of Markov Chains ([arxiv, 2022](https://arxiv.org/abs/2203.04575))
- Information Geometry of Reversible Markov Chains ([Information Geometry, 2021](https://link.springer.com/article/10.1007/s41884-021-00061-7))
- Geometry of Markov Chains, Finite State Machines, and Tree Models ([IEICE Tech. Rep., 2014](https://www.ieice.org/ken/paper/20140718BBPQ/eng/))
- Information geometry approach to parameter estimation in Markov chains ([ISIT, 2014](https://ieeexplore.ieee.org/abstract/document/6875001))
- Information geometry and sequential Monte Carlo ([arXiv, 2012](https://arxiv.org/abs/1212.0764))
- Information Geometry of Contrastive Divergence ([ITSL, 2008](https://staff.aist.go.jp/s.akaho/papers/itsl2008.pdf))
- Information geometry of Gibbs sampler ([NNA, 2004](https://staff.aist.go.jp/k.takabatake/takabatake04.pdf))

## Information Geometry for HMM
- Information geometry approach to parameter estimation in hidden Markov model ([Bernoulli, 2022](https://projecteuclid.org/journals/bernoulli/volume-28/issue-1/Information-geometry-approach-to-parameter-estimation-in-hidden-Markov-model/10.3150/21-BEJ1344.short))
- Local equivalence problem in hidden Markov model ([Information Geometry, 2019](https://link.springer.com/article/10.1007/s41884-019-00016-z))

## Information Geometry for Dimension Reduction
- Generalized t-SNE Through the Lens of Information Geometry ([IEEE Access, 2021](https://ieeexplore.ieee.org/abstract/document/9540693/))
- Dimension Reduction for Mixtures of Exponential Families ([ICANN, 2008](https://link.springer.com/chapter/10.1007/978-3-540-87536-9_1))
- The e-PCA and m-PCA: Dimension reduction of parameters by information geometry ([IJCNN, 2004](https://ieeexplore.ieee.org/abstract/document/1379884))

## Information Geometry and Optimization
- On a Cornerstone of Bare-Simulation Distance/Divergence Optimization ([GSI, 2023](https://link.springer.com/chapter/10.1007/978-3-031-38271-0_11))

## Fisher Information Matrix
- FIT: A Metric for Model Sensitivity ([ICLR, 2023](https://openreview.net/forum?id=PDG4-Y3aboN))
- A Statistical Manifold Framework for Point Cloud Data ([ICML, 2022](https://proceedings.mlr.press/v162/lee22d.html))
- On the Variance of the Fisher Information for Deep Learning ([NeurIPS, 2021](https://papers.nips.cc/paper/2021/hash/2d290e496d16c9dcaa9b4ded5cac10cc-Abstract.html))
- On the Fisher-Rao Information Metric in the Space of Normal Distributions ([GSI, 2019](https://link.springer.com/chapter/10.1007/978-3-030-26980-7_70))
- The Spectrum of the Fisher Information Matrix of a Single-Hidden-Layer Neural Network ([NeurIPS, 2018](https://papers.nips.cc/paper/2018/hash/18bb68e2b38e4a8ce7cf4f6b2625768c-Abstract.html))
- General Fisher information matrices of a random vector ([Adv. Appl. Math., 2017](https://www.sciencedirect.com/science/article/pii/S0196885817300404))
- Evaluating neuronal codes for inference using Fisher information ([NeurIPS, 2010](https://papers.nips.cc/paper/2010/hash/08b255a5d42b89b0585260b6f2360bdd-Abstract.html))
- Invariant Fisher information ([Differ Geom Appl., 1994](https://www.sciencedirect.com/science/article/pii/0926224594000131))

## Fisher Kernels
- Learning Representation from Neural Fisher Kernel with Low-rank Approximation ([ICLR, 2022](https://openreview.net/forum?id=J1rhANsCY9))
- Deep active learning for biased datasets via fisher kernel self-supervision ([CVPR, 2020](https://openaccess.thecvf.com/content_CVPR_2020/html/Gudovskiy_Deep_Active_Learning_for_Biased_Datasets_via_Fisher_Kernel_Self-Supervision_CVPR_2020_paper.html))
- Persistence fisher kernel: A riemannian manifold kernel for persistence diagrams ([NeurIPS, 2018](https://proceedings.neurips.cc/paper/2018/hash/959ab9a0695c467e7caf75431a872e5c-Abstract.html))
- The fisher kernel: a brief review ([RN, 2011](http://www.cs.ucl.ac.uk/fileadmin/UCL-CS/research/Research_Notes/RN_11_06.pdf))
- Improving the fisher kernel for large-scale image classification ([ECCV, 2010](https://link.springer.com/chapter/10.1007/978-3-642-15561-1_11))
- Indefinite kernel fisher discriminant ([ICPR, 2008](https://ieeexplore.ieee.org/abstract/document/4761718/))
- A Kullback-Leibler divergence based kernel for SVM classification in multimedia applications ([NeurIPS, 2003](https://proceedings.neurips.cc/paper/2003/hash/0abdc563a06105aee3c6136871c9f4d1-Abstract.html))
- A novel graph-based fisher kernel method for semi-supervised learning ([ICPR, 2014](https://ieeexplore.ieee.org/abstract/document/6977362))
- Learning the Similarity of Documents: An Information-Geometric Approach to Document Retrieval and Categorization ([NeurIPS, 1999](https://papers.nips.cc/paper/1999/hash/9d2682367c3935defcb1f9e247a97c0d-Abstract.html))
 
## Information Diffusion Kernels
- Learning parameterized histogram kernels on the simplex manifold for image and action classification ([ICCV, 2011](https://ieeexplore.ieee.org/abstract/document/6126404/))
- Sentiment classification with interpolated information diffusion kernels ([ADKDD, 2007](https://dl.acm.org/doi/abs/10.1145/1348599.1348605))
- Diffusion kernels on statistical manifolds ([JMLR, 2005](https://www.jmlr.org/papers/volume6/lafferty05a/lafferty05a.pdf?fbclid=IwAR0nnU0pveoflyoS5msfIi5fcpZh8FQziAqaLICe1BWMZQcLe7uKT1kCI5A))

## Natural Gradients
- Linear Convergence of Natural Policy Gradient Methods with Log-Linear Policies ([ICLR, 2023](https://openreview.net/forum?id=-z9hdsyUwVQ))
- Invariance properties of the natural gradient in overparametrised systems ([Information Geometry, 2022](https://link.springer.com/article/10.1007/s41884-022-00067-9))
- Tractable structured natural-gradient descent using local parameterizations ([ICML, 2021](https://proceedings.mlr.press/v139/lin21e.html))
- Marginalized Stochastic Natural Gradients for Black-Box Variational Inference ([ICML, 2021](https://proceedings.mlr.press/v139/ji21b.html))
- Sinkhorn Natural Gradient for Generative Models ([NeurIPS, 2020](https://papers.nips.cc/paper/2020/hash/122e27d57ae8ecb37f3f1da67abb33cb-Abstract.html))
- An Improved Analysis of (Variance-Reduced) Policy Gradient and Natural Policy Gradient Methods ([NeurIPS, 2020](https://papers.nips.cc/paper/2020/hash/56577889b3c1cd083b6d7b32d32f99d5-Abstract.html))
- Natural Policy Gradient Primal-Dual Method for Constrained Markov Decision Processes ([NeurIPS, 2020](https://papers.nips.cc/paper/2020/hash/5f7695debd8cde8db5abcb9f161b49ea-Abstract.html))
- Understanding Approximate Fisher Information for Fast Convergence of Natural Gradient Descent in Wide Neural Networks ([NeurIPS, 2020](https://papers.nips.cc/paper/2020/hash/7b41bfa5085806dfa24b8c9de0ce567f-Abstract.html))
- Ngboost: Natural gradient boosting for probabilistic prediction ([ICML, 2020](http://proceedings.mlr.press/v119/duan20a.html?ref=https://githubhelp.com))
- A Formalization of the Natural Gradient Method for General Similarity Measures ([GSI, 2019](https://link.springer.com/chapter/10.1007/978-3-030-26980-7_62))
- Fast Convergence of Natural Gradient Descent for Over-Parameterized Neural Networks ([NeurIPS, 2019](https://papers.nips.cc/paper/2019/hash/1da546f25222c1ee710cf7e2f7a3ff0c-Abstract.html))
- Limitations of the empirical Fisher approximation for natural gradient descent ([NeurIPS, 2019](https://papers.nips.cc/paper/2019/hash/46a558d97954d0692411c861cf78ef79-Abstract.html))
- Adaptive Stochastic Natural Gradient Method for One-Shot Neural Architecture Search ([ICML, 2019](https://proceedings.mlr.press/v97/akimoto19a.html))
- Online natural gradient as a Kalman filter ([Electron. J. Stat., 2018](https://projecteuclid.org/journals/electronic-journal-of-statistics/volume-12/issue-2/Online-natural-gradient-as-a-Kalman-filter/10.1214/18-EJS1468.full))
- Fast yet simple natural-gradient descent for variational inference in complex models ([ISITA, 2018](https://ieeexplore.ieee.org/abstract/document/8664326))
- Natural gradient via optimal transport ([Information Geometry, 2018](https://link.springer.com/article/10.1007/s41884-018-0015-3))
- Fast Approximate Natural Gradient Descent in a Kronecker Factored Eigenbasis ([NeurIPS, 2018](https://papers.nips.cc/paper/2018/hash/48000647b315f6f00f913caa757a70b3-Abstract.html))
- Exact natural gradient in deep linear networks and its application to the nonlinear case ([NeurIPS, 2018](https://papers.nips.cc/paper/2018/hash/7f018eb7b301a66658931cb8a93fd6e8-Abstract.html))
- SLANG: Fast Structured Covariance Approximations for Bayesian Deep Learning with Natural Gradient ([NeurIPS, 2018](https://papers.nips.cc/paper/2018/hash/d3157f2f0212a80a5d042c127522a2d5-Abstract.html))
- Comparison-based natural gradient optimization in high dimension ([GECCO, 2014](https://dl.acm.org/doi/abs/10.1145/2576768.2598258))
- Projected Natural Actor-Critic ([NeurIPS, 2013](https://papers.nips.cc/paper/2013/hash/dd77279f7d325eec933f05b1672f6a1f-Abstract.html))
- Stochastic Gradient Riemannian Langevin Dynamics on the Probability Simplex ([NeurIPS, 2013](https://papers.nips.cc/paper/2013/hash/309928d4b100a5d75adff48a9bfc1ddb-Abstract.html))
- New Sparse Adaptive Algorithms Based on the Natural Gradient and the $L_0$-Norm  ([IEEE J. Ocean. Eng., 2012](https://ieeexplore.ieee.org/abstract/document/6365766))
- Natural Policy Gradient Methods with Parameter-based Exploration for Control Tasks ([NeurIPS, 2010](https://papers.nips.cc/paper/2010/hash/44c4c17332cace2124a1a836d9fc4b6f-Abstract.html))
- A Generalized Natural Actor-Critic Algorithm ([NeurIPS, 2009](https://papers.nips.cc/paper/2009/hash/acf4b89d3d503d8252c9c4ba75ddbf6d-Abstract.html))
- Stochastic search using the natural gradient ([ICML, 2009](https://dl.acm.org/doi/abs/10.1145/1553374.1553522?casa_token=fo1cfbAvRXUAAAAA:2AOY3ZmMcvl_qDx9hWVil95hF7P6QrjZu5VJWo-6EBWoYkMLqc0oa9qcl0Jy-I09BSSME-h1Q9_72g))
- Incremental Natural Actor-Critic Algorithms ([NeurIPS, 2007](https://papers.nips.cc/paper/2007/hash/6883966fd8f918a4aa29be29d2c386fb-Abstract.html))
- Topmoumoute Online Natural Gradient Algorithm ([NeurIPS, 2007](https://papers.nips.cc/paper/2007/hash/9f61408e3afb633e50cdf1b20de6f466-Abstract.html))
- Natural Actor-Critic for Road Traffic Optimisation ([NeurIPS, 2006](https://papers.nips.cc/paper/2006/hash/78bc62d08a9a0b9b0b9c0ad339ef82d3-Abstract.html))
- Rprop using the natural gradient ([Trends and Applications in Constructive Approximation, 2005](https://link.springer.com/chapter/10.1007/3-7643-7356-3_19))
- A Natural Policy Gradient ([NeurIPS, 2001](https://papers.nips.cc/paper/2001/hash/4b86abe48d358ecf194c56c69108433e-Abstract.html))
- Natural gradient descent for on-line learning ([PRL, 1998](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.81.5461))
- Natural gradient works efficiently in learning ([Neural Computation, 1998](https://ieeexplore.ieee.org/abstract/document/6790500))

## Statistical Manifolds and Hessian Information Geometry
- On the Tangent Bundles of Statistical Manifolds ([GSI, 2023](https://link.springer.com/chapter/10.1007/978-3-031-38271-0_20))
- Geometric Properties of Beta Distributions ([GSI, 2023](https://link.springer.com/chapter/10.1007/978-3-031-38271-0_21))
- KV Cohomology Group of Some KV Structures on ℝ^2 ([GSI, 2023](https://link.springer.com/chapter/10.1007/978-3-031-38271-0_22))
- Alpha-parallel Priors on a One-Sided Truncated Exponential Family ([GSI, 2023](https://link.springer.com/chapter/10.1007/978-3-031-38271-0_23))
- Conformal Submersion with Horizontal Distribution and Geodesics ([GSI, 2023](https://link.springer.com/chapter/10.1007/978-3-031-38271-0_24))

## alpha-Divergence
- Infinite-dimensional gradient-based descent for alpha-divergence minimisation ([Ann. Stat., 2021](https://projecteuclid.org/journals/annals-of-statistics/volume-49/issue-4/Infinite-dimensional-gradient-based-descent-for-alpha-divergence-minimisation/10.1214/20-AOS2035.short))
- Utilizing amari-alpha divergence to stabilize the training of generative adversarial networks ([Entropy, 2020](https://www.mdpi.com/1099-4300/22/4/410))
- Divergence Functions in Information Geometry ([GSI, 2019](https://link.springer.com/chapter/10.1007/978-3-030-26980-7_45))
- Log-determinant divergences revisited: Alpha-beta and gamma log-det divergences ([Entropy, 2015](https://www.mdpi.com/1099-4300/17/5/2988))
- On the chi square and higher-order chi distances for approximating f-divergences ([IEEE Signal Processing Letters, 2013](https://ieeexplore.ieee.org/abstract/document/6654274))
- Families of alpha-beta-and gamma-divergences: Flexible and robust measures of similarities ([Entropy, 2010](https://www.mdpi.com/1099-4300/12/6/1532))
- Information geometry of divergence functions ([Bull. Pol. Acad. Sci. Tech. Sci., 2010](https://www.infona.pl/resource/bwmeta1.element.baztech-article-BPG8-0020-0019))
- $\alpha $-Divergence Is Unique, Belonging to Both $f$-Divergence and Bregman Divergence Classes ([IEEE Trans. Information Theory, 2009](https://ieeexplore.ieee.org/abstract/document/5290302))
- Non-negative matrix factorization with $\alpha$-divergence ([Pattern Recognit. Lett., 2008](https://www.sciencedirect.com/science/article/abs/pii/S0167865508000767))
- Integration of Stochastic Models by Minimizing $\alpha$-Divergence ([Neural Computation, 2007](https://ieeexplore.ieee.org/abstract/document/6795912))

## Bregman Divergence
- Neural Bregman Divergences for Distance Learning ([ICLR, 2023](https://openreview.net/forum?id=nJ3Vx78Nf7p))
- Transport information Bregman divergences ([Information Geometry, 2021](https://link.springer.com/article/10.1007/s41884-021-00063-5))
- Target detection within nonhomogeneous clutter via total bregman divergence-based matrix information geometry detectors ([IEEE Trans. Signal Processing, 2021](https://ieeexplore.ieee.org/abstract/document/9479799))
- The Bregman Chord Divergence ([GSI, 2019](https://link.springer.com/chapter/10.1007/978-3-030-26980-7_31))
- Logarithmic Divergences: Geometry and Interpretation of Curvature ([GSI, 2019](https://link.springer.com/chapter/10.1007/978-3-030-26980-7_43))
- Information geometry for radar target detection with total Jensen–Bregman divergence ([Entropy, 2018](https://www.mdpi.com/1099-4300/20/4/256))
- Information geometry for covariance estimation in heterogeneous clutter with total Bregman divergence ([Entropy, 2018](https://www.mdpi.com/280084))
- The information geometry of mirror descent ([IEEE Trans. Information Theory, 2015](https://ieeexplore.ieee.org/abstract/document/7004065/))
- The information geometry of Bregman divergences and some applications in multi-expert reasoning ([Entropy, 2014](https://www.mdpi.com/85934))
- Information geometry of U-Boost and Bregman divergence ([Neural Computation, 2004](https://ieeexplore.ieee.org/document/6789609))

## Jensen-Shannon Divergence
- Quasi-arithmetic Centers, Quasi-arithmetic Mixtures, and the Jensen-Shannon ∇-Divergences ([GSI, 2023](https://link.springer.com/chapter/10.1007/978-3-031-38271-0_15))
- On a variational definition for the Jensen-Shannon symmetrization of distances based on the information radius ([Entropy, 2021](https://www.mdpi.com/1099-4300/23/4/464))
- $\alpha$-Geodesical Skew Divergence ([Entropy, 2021](https://www.mdpi.com/1099-4300/23/5/528))
- On a generalization of the Jensen–Shannon divergence and the Jensen–Shannon centroid ([Entropy, 2020](https://www.mdpi.com/1099-4300/22/2/221))
- On the Jensen–Shannon Symmetrization of Distances Relying on Abstract Means ([Entropy, 2019](https://www.mdpi.com/1099-4300/21/5/485/htm))

## Exponential and Mixture Families
- On partial likelihood and the construction of factorisable transformations ([Information Geometry, 2022](https://link.springer.com/article/10.1007/s41884-022-00068-8))
- On a convergence property of a geometrical algorithm for statistical manifolds ([ICONIP, 2019](https://link.springer.com/chapter/10.1007/978-3-030-36802-9_29))
- Testing the Number and the Nature of the Components in a Mixture Distribution ([GSI, 2019](https://link.springer.com/chapter/10.1007/978-3-030-26980-7_32))
- Sobolev Statistical Manifolds and Exponential Models ([GSI, 2019](https://link.springer.com/chapter/10.1007/978-3-030-26980-7_46))
- Minimization of the Kullback-Leibler Divergence over a Log-Normal Exponential Arc ([GSI, 2019](https://link.springer.com/chapter/10.1007/978-3-030-26980-7_47))
- Riemannian Distance and Diameter of the Space of Probability Measures and the Parametrix ([GSI, 2019](https://link.springer.com/chapter/10.1007/978-3-030-26980-7_48))
- Information geometry of positive measures and positive-definite matrices: decomposable dually flat structure ([Entropy, 2014](https://www.mdpi.com/1099-4300/16/4/2131))
- Geometry of deformed exponential families: Invariant, dually-flat and conformal geometries ([Physica A, 2012](https://www.sciencedirect.com/science/article/pii/S037843711200310X?casa_token=5QWUwzlQnr0AAAAA:bWGXoEe3_Tw7fi-1AMPgCW0o7dGx2ZAyof3A_mG3Mwqp00MmxDeiXA5rLq-vejdfboyLam-vYto))
- Geometry of q-Exponential Family of Probability Distributions ([Entropy, 2011](https://www.mdpi.com/1099-4300/13/6/1170))

## Inequalities
- Curvature Inequalities and Simons’ Type Formulas in Statistical Geometry ([GSI, 2021](https://link.springer.com/chapter/10.1007/978-3-030-80209-7_43))
- Inequalities for Statistical Submanifolds in Hessian Manifolds of Constant Hessian Curvature ([GSI, 2019](https://link.springer.com/chapter/10.1007/978-3-030-26980-7_40))
- B. Y. Chen Inequalities for Statistical Submanifolds in Sasakian Statistical Manifolds ([GSI, 2019](https://link.springer.com/chapter/10.1007/978-3-030-26980-7_41))
- Generalized Wintgen Inquality for Legendrian Submanifolds in Sasakian Statistical Manifolds ([GSI, 2019](https://link.springer.com/chapter/10.1007/978-3-030-26980-7_42))
- Cramér-Rao lower bound and information geometry ([Connected at Infinity II., 2013](https://link.springer.com/chapter/10.1007/978-93-86279-56-9_2))
- Inequalities for Tsallis relative entropy and generalized skew information ([Linear Multilinear Algebra, 2011](https://www.tandfonline.com/doi/abs/10.1080/03081087.2011.574624))

## Transport Information Geometry
- Riemannian Metric Learning via Optimal Transport ([ICLR, 2023](https://openreview.net/forum?id=v3y68gz-WEz))
- Wasserstein information matrix ([Information Geometry, 2023](https://link.springer.com/article/10.1007/s41884-023-00099-9))
- Wasserstein Statistics in One-Dimensional Location-Scale Models ([GSI, 2021](https://link.springer.com/chapter/10.1007/978-3-030-80209-7_54))
- Traditional and Accelerated Gradient Descent for Neural Architecture Search ([GSI, 2021](https://link.springer.com/chapter/10.1007/978-3-030-80209-7_55))
- Recent Developments on the MTW Tensor ([GSI, 2021](https://link.springer.com/chapter/10.1007/978-3-030-80209-7_56))
- Wasserstein Proximal of GANs ([GSI, 2021](https://link.springer.com/chapter/10.1007/978-3-030-80209-7_57))
- Hessian Curvature and Optimal Transport ([GSI, 2019](https://link.springer.com/chapter/10.1007/978-3-030-26980-7_44))
- Information geometry connecting Wasserstein distance and Kullback–Leibler divergence via the entropy-relaxed transportation problem ([Information Geometry, 2018](https://link.springer.com/article/10.1007/s41884-018-0002-8))

## Computational Information Geometry
- λ-Deformed Evidence Lower Bound (λ-ELBO) Using Rényi and Tsallis Divergence ([GSI, 2023](https://link.springer.com/chapter/10.1007/978-3-031-38271-0_19))
- On the f-Divergences Between Hyperboloid and Poincaré Distributions ([GSI, 2023](https://link.springer.com/chapter/10.1007/978-3-031-38271-0_18))
- Geometry of Parametric Binary Choice Models ([GSI, 2023](https://link.springer.com/chapter/10.1007/978-3-031-38271-0_16))
- A q-Analogue of the Family of Poincaré Distributions on the Upper Half Plane ([GSI, 2023](https://link.springer.com/chapter/10.1007/978-3-031-38271-0_17))
- Computing Statistical Divergences with Sigma Points ([GSI, 2021](https://link.springer.com/chapter/10.1007/978-3-030-80209-7_72))
- Remarks on Laplacian of Graphical Models in Various Graphs ([GSI, 2021](https://link.springer.com/chapter/10.1007/978-3-030-80209-7_73))
- Classification in the Siegel Space for Vectorial Autoregressive Data ([GSI, 2021](https://link.springer.com/chapter/10.1007/978-3-030-80209-7_74))
- Information Metrics for Phylogenetic Trees via Distributions of Discrete and Continuous Characters ([GSI, 2021](https://link.springer.com/chapter/10.1007/978-3-030-80209-7_75))
- Wald Space for Phylogenetic Trees ([GSI, 2021](https://link.springer.com/chapter/10.1007/978-3-030-80209-7_76))
- A Necessary Condition for Semiparametric Efficiency of Experimental Designs ([GSI, 2021](https://link.springer.com/chapter/10.1007/978-3-030-80209-7_77))
- Parametrisation Independence of the Natural Gradient in Overparametrised Systems ([GSI, 2021](https://link.springer.com/chapter/10.1007/978-3-030-80209-7_78))
- Properties of Nonlinear Diffusion Equations on Networks and Their Geometric Aspects ([GSI, 2021](https://link.springer.com/chapter/10.1007/978-3-030-80209-7_79))
- Rényi Relative Entropy from Homogeneous Kullback-Leibler Divergence Lagrangian ([GSI, 2021](https://link.springer.com/chapter/10.1007/978-3-030-80209-7_80))
- Statistical Bundle of the Transport Model ([GSI, 2021](https://link.springer.com/chapter/10.1007/978-3-030-80209-7_81))
- Topological Methods for Unsupervised Learning ([GSI, 2019](https://link.springer.com/chapter/10.1007/978-3-030-26980-7_35))
- Geometry and Fixed-Rate Quantization in Riemannian Metric Spaces Induced by Separable Bregman Divergences ([GSI, 2019](https://link.springer.com/chapter/10.1007/978-3-030-26980-7_36))
- The Statistical Minkowski Distances: Closed-Form Formula for Gaussian Mixture Models ([GSI, 2019](https://link.springer.com/chapter/10.1007/978-3-030-26980-7_37))
- Parameter Estimation with Generalized Empirical Localization ([GSI, 2019](https://link.springer.com/chapter/10.1007/978-3-030-26980-7_38))
- Properties of the Cross Entropy Between ARMA Processes ([GSI, 2019](https://link.springer.com/chapter/10.1007/978-3-030-26980-7_39))
- Computational information geometry for binary classification of high-dimensional random tensors ([Entropy, 2018](https://www.mdpi.com/1099-4300/20/3/203))
- Computational information geometry in statistics: theory and practice ([Entropy, 2014](https://www.mdpi.com/1099-4300/16/5/2454))
- Computational Information Geometry and its Applications ([ICNNB, 2005](https://ieeexplore.ieee.org/abstract/document/1614550))

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
- International Conference on Geometric Science of Information ([GSI](https://link.springer.com/conference/gsi))
 
# Workshops
- Symmetry and Geometry in Neural Representations ([at NeurIPS 2022](https://sites.google.com/view/neur-reps/home))
- TAG in Machine Learning ([at ICML 2022](https://www.tagds.com/events/conferences/tag-in-machine-learning))
- Deep Learning through Information Geometry ([at NeurIPS 2020](https://sites.google.com/view/dl-info-neurips20))
