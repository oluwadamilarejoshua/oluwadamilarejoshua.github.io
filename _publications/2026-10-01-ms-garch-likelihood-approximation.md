---
title: "Likelihood Approximation Choices and the Performance of Markov-Switching GARCH Models: Evidence from Thirty Global Financial Assets"
collection: publications
category: working
permalink: /publication/ms-garch-likelihood-approximation
authors: "<b>Joshua Ogundairo</b> and Oluwadare O. Ojo"
status: "MTech thesis. Accepted for poster presentation, <a href='https://www.cmstatistics.org/RegistrationsV2/CFECMStatistics2026/viewSubmission.php?id=1267&token=349o84s752r633708359o160nr364n38'>CFE-CMStatistics 2026</a>, Berlin."
excerpt: "Compares four likelihood approximations for MS-GARCH models on thirty assets in five markets, and shows that the choice of approximation, which applied work rarely reports, changes the results."
date: 2026-10-01
venue: "MTech thesis, Federal University of Technology, Akure"
---

**Abstract.** Exact likelihood evaluation for Markov-switching GARCH(1,1) models is computationally intractable, so practitioners rely on approximations, yet there is little systematic evidence on how the choice of approximation affects model performance. This study implements and compares four likelihood approximations (Gray's collapsing procedure, plug-in approximation, Gaussian quadrature, and the particle filter) on 30 financial assets from five market archetypes: cryptocurrencies, foreign exchange, equities, bonds, and derivatives. Baseline specifications capture internal volatility dynamics, and exogenous specifications add cross-market spillover variables. Assets are grouped into four kurtosis cohorts to test how tail behaviour moderates approximation performance.

Gray's method and plug-in approximation deliver the best log-likelihood optimisation for assets with well-behaved return distributions. The particle filter converges in every case but consistently underperforms in likelihood maximisation across all asset classes. Exogenous conditioning substantially improves fit and regularises the likelihood surface for most assets, though it introduces localised numerical instability for extreme-tail instruments. The study recommends plug-in or quadrature approximations for heterogeneous portfolios, reserves Gray's method for low-kurtosis applications, and cautions against the particle filter as a primary estimator.

**My role.** I designed the study and its 220-case experiment, built a C++ likelihood engine interfaced with Python via Cython (a 36-fold speed-up), ran all estimation, and wrote the thesis.
