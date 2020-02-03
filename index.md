# Workshop on Emerging Themes in Computational Statistics
__Dates: 19th (Wed) &mdash; 20th (Thu) February, 2020__  
__Location: [The Institute of Statistical Mathematics, Tokyo, Japan](https://goo.gl/maps/58QJ35GUTkLtmDEQ9)__  
__Registration: No registration required (except for dinner)__

### Outline

Computational statistics is a rapidly developing research field due to the increasing
high demand in analysing large and complex data in many areas of science. Motivated
by the recent innovations in efficient computational techniques for statistical
inference and a variety of computationally challenging applications, this workshop aims
to facilitate discussions amongst researchers working on different aspects of statistical
computations, and promotes new ideas in both methodological and applied directions.

### Timetable

|                     |      Day 1 (19 Feb)     |   Day 2 (20 Feb)   |
|:-------------------:|:-----------------------:|:------------------:|
|  9:30 &ndash; 10:30 |       Chris Oates       |    Scott Sisson    |
| 10:30 &ndash; 11:00 |      _Coffee break_     |   _Coffee break_   |
| 11:00 &ndash; 12:00 |  Francois-Xavier Briol  |   Richard Gerlach  |
| 12:00 &ndash; 13:30 |         _Lunch_         |       _Lunch_      |
| 13:30 &ndash; 14:30 |    Heishiro Kanagawa    |  Pavel Shevchenko  |
| 14:30 &ndash; 15:00 |     _Afternoon tea_     |   _Afternoon tea_  |
| 15:00 &ndash; 16:00 |     Shin-Itiro Goto     |   Takeru Matsuda   |
| 16:00 &ndash; 17:00 |        Wenkai Xu        |  Daisuke Murakami  |
| 19:00 &ndash; late  |  _Dinner & Discussion_  |                    |

### Speakers

* __Chris Oates (Newcastle University, Alan Turing Institute, UK)__  
  __Title:__ Gaussian Process Approximation of Deterministic Functions  
  __Abstract:__ Despite the ubiquity of Gaussian process regression in the applied context, almost no theoretical results are available that account for the fact that parameters of the covariance kernel need to be jointly estimated from the dataset. The lack of theoretical understanding draws into question whether Gaussian process regression should be used at all in important, e.g. safety-critical, applications. To gain some insight, we studied the scenario where the scale parameter of the kernel is estimated using maximum likelihood. Our main result is a bound on the rate at which the Gaussian process can become overconfident as the size of the dataset is increased. The analysis is based on a combination of techniques from nonparametric regression and scattered data interpolation, and is joint work with Toni Karvonen, George Wynne, Filip Tronarp and Simo Särkkä.  

* __Francois-Xavier Briol (University College London, Alan Turing Institute, UK)__  
  __Title:__ Statistical Inference for Generative Models with Maximum Mean Discrepancy  
  __Abstract:__ While likelihood-based inference and its variants provide a statistically efficient and widely applicable approach to parametric inference, their application to models involving intractable likelihoods poses challenges. In this work, we study a class of minimum distance estimators for intractable generative models, that is, statistical models for which the likelihood is intractable, but simulation is cheap. The distance considered, maximum mean discrepancy (MMD) is defined through the embedding of probability measures into a reproducing kernel Hilbert space (RKHS). We study the theoretical properties of these estimators, showing that they are consistent and asymptotically normal. A main advantage of these estimators is the flexibility offered by the choice of kernel, which can be used to trade-off statistical efficiency and robustness. Studying the geometry induced by MMD on the parameter space, we introduce a novel natural gradient descent-like algorithm for efficient implementation of these estimators. We illustrate the relevance of our theoretical results on several classes of models including a discrete-time latent Markov process and a multivariate stochastic differential equation model.  

* __Heishiro Kanagawa (University College London, UK)__  
  __Title:__ A Kernel Stein Test for Comparing Latent Variable Models  
  __Abstract:__ I will present a nonparametric, kernel-based test to assess the relative goodness of fit of latent variable models with intractable unnormalized densities. The test generalises the kernel Stein discrepancy (KSD) tests of (Liu et al., 2016, Chwialkowski et al., 2016, Yang et al., 2018, Jitkrittum et al., 2018) which required exact access to unnormalized densities. It relies on the simple idea of using an approximate observed-variable marginal in place of the exact, intractable one. As our main theoretical contribution, we prove that the new test, with a properly corrected threshold, has a well-controlled type-I error. In the case of models with low-dimensional latent structure and high-dimensional observations, our test significantly outperforms the relative maximum mean discrepancy test (Bounliphone et al., 2015), which cannot exploit the latent structure.  

* __Shin-Itiro Goto (Institute of Statistical Mathematics, Japan)__  
  __Title:__ Information and Contact Geometries for Expectation Variables Exactly Derived From a Class of Master Equations  
  __Abstract:__  Information geometry is a discipline that studies differential geometric aspects of statistics, and has contributed to progress in mathematics and engineering applications including Monte-Carlo simulation techniques. Monte-Carlo techniques are formulated based on the theory of Markov chains, where Markov chains are modeled as master equations that have been studied in statistical mechanics and thermodynamics. Contact geometry is known as an odd-dimensional counterpart of symplectic geometry, and has been applied to build differential geometric statistical mechanics and thermodynamics. Although such applications exist in the literature, many pure mathematical findings in contact geometry have not yet been applied. Since some mathematical ideas, including Legendre transform and conjugate variables, are commonly used in thermodynamics, contact geometry, and information geometry, an amalgamation of these geometries is expected to be fruitful in the studies of thermodynamics and Monte-Carlo techniques. Thus, how theorems found in these differential geometries can be used should be explored in the application areas above. In this talk we propose a class of continuous-time master equations, and show how information-contact geometric tools can be used. Here this class is simple enough to exactly derive a dynamical system for expectation variables from the master equations, and allows to discuss a relaxation process in a differential geometric manner.  

* __Wenkai Xu (University College London, UK)__  
  __Title:__ A Stein Goodness-of-fit Test for Directional Distributions  
  __Abstract:__ In many fields, data appears in the form of direction (unit vector) and usual statistical procedures are not applicable to such directional data. In this study, we propose non-parametric goodness-of-fit testing procedures for general directional distributions based on kernel Stein discrepancy. Our method is based on Stein's operator on spheres, which is derived by using Stokes' theorem. Notably, the proposed method is applicable to distributions with an intractable normalization constant, which commonly appear in directional statistics. Experimental results demonstrate that the proposed methods control type-I error well and have larger power than existing tests, including the test based on the maximum mean discrepancy.  

* __Scott Sisson (University of New South Wales, Australia)__  
  __Title:__ New Models for Distributional-Based Data  
  __Abstract:__  There has been much recent interest in developing statistical methods that can handle large-scale and complex data. One such approach is based on the idea of reducing the data to a smaller number of summary distributions &mdash; such as random histograms, or random intervals &mdash; that describe where the data generally reside, at the loss of some information about where each data point is precisely located. These distributions are then used as summary statistics in a standard analysis, with the benefit of large computational savings. This talk will outline some recent results and applications in this area.  

* __Richard Gerlach (University of Sydney, Australia)__  
  __Title:__ A Semi-parametric Realized Joint Value-at-Risk and Expected Shortfall Regression Framework  
  __Abstract:__ A new realized joint Value-at-Risk (VaR) and expected shortfall (ES) regression framework is proposed, through incorporating a measurement equation into the original joint VaR and ES regression model of Taylor (2017). The measurement equation models the contemporaneous dependence between the realized measure (e.g. Realized Variance and Realized Range) and the latent conditional quantile. Further, sub-sampling and scaling methods are applied to both the realized range and realized variance, to help deal with inherent micro-structure noise and inefficiency. An adaptive Bayesian Markov Chain Monte Carlo method is employed for estimation and forecasting, whose properties are assessed and compared with maximum likelihood estimator through simulation study. In a forecasting study, the proposed models are applied to 7 market indices and 7 individual assets, compared to a range of parametric, non-parametric and semi-parametric models, including GARCH, Realized-GARCH, conditional autoregressive Expectile and Taylor (2017)  joint VaR and ES quantile regression models, one-day-ahead Value-at-Risk and Expected Shortfall forecasting results favor the proposed models, especially when incorporating the sub-sampled Realized Variance and the sub-sampled Realized Range in the model.  

* __Pavel Shevchenko (Macquarie University, Australia)__  
  __Title:__  
  __Abstract:__  

* __Takeru Matsuda (University of Tokyo, Japan)__  
  __Title:__ Information Criteria for Non-Normalized Models  
  __Abstract:__ Many statistical models are given in the form of non-normalized densities with an intractable normalization constant. Since maximum likelihood estimation is computationally intensive for these models, several estimation methods have been developed which do not require explicit computation of the normalization constant, such as noise contrastive estimation (NCE) and score matching. However, model selection methods for general non-normalized models have not been proposed so far. In this study, we develop information criteria for non-normalized models estimated by NCE or score matching. They are derived as approximately unbiased estimators of discrepancy measures for non-normalized models. Experimental results demonstrate that the proposed criteria enable selection of the appropriate non-normalized model in a data-driven manner. Extension to a finite mixture of non-normalized models is also discussed.  

* __Daisuke Murakami (Institute of Statistical Mathematics, Japan)__  
  __Title:__  A Scalable Spatial Additive Modeling for Large Dataset  
  __Abstract:__  Regression problem for large samples is now commonplace, and fast and memory-efficient egression models accommodating group effects, non-linear effects, and other effects are increasingly important. This study develops a spatial additive regression approach for large samples. Therein, we developed an algorithm estimating spatial and non-spatial effects whose computational complexity and memory consumption are independent of the sample size after pre-conditioning. The performance of the developed approach is examined through Monte Carlo simulation experiments and empirical application.  

### Lunch

Popular lunch spots around ISM:
* Tachikawa City Hall (立川市役所)
* Bento boxes at Polar Science Museum (南極・北極科学館)
* Zuikyo Chinese Restaurant (中国料理・瑞京)
* Lalaport Tachikawa (ららぽーと立川立飛店)
* Tokyo District Court Tachikawa Branch (東京地方裁判所)
* Local Autonomy College (自治大学校)

### Dinner

TBA

### Accommodation

* [Palace Hotel Tachikawa](https://www.palace-t.co.jp/english/)
* [Tachikawa Grand Hotel](https://www.guestreservations.com/tachikawa-grand-hotel/booking)
* [Hotel Nikko Tachikawa](https://www.okura-nikko.com/japan/tokyo/hotel-nikko-tachikawa-tokyo/)

### Organisation

* Wilson Chen, wilson(at-symbol)ism.ac.jp
* Yi Jiang, jiangyi(at-symbol)ism.ac.jp
* Tomoko Matsui, tmatsui(at-symbol)ism.ac.jp

### Acknowledgement

This workshop is supported by the Risk Analysis Research Center, Institute of Statistical Mathematics.
