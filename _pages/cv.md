---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

**[Download my full CV (PDF)]({{ base_path }}/files/Joshua_Ogundairo_CV.pdf)**

Education
======
* **MTech in Statistics**, Federal University of Technology, Akure (FUTA), 2024 – 2026
  * CGPA 4.53/5.0; Distinction (expected October 2026)
  * Thesis: *Likelihood Approximation Choices and the Performance of Markov-Switching GARCH Models*
  * Advisor: Prof. Oluwadare O. Ojo
* **BTech in Statistics**, FUTA, 2015 – 2021
  * CGPA 3.76/5.0; Second Class Upper Division

Research
======
Two working papers and two journal articles in time series analysis, Bayesian inference, and financial econometrics. See the [Research](/publications/) page for summaries and my role in each.

Positions
======
* **Senior Coordinator, Data Scientist**, eHealth Africa, Abuja, Dec 2025 – present
  * Leads a research portfolio of five spatial-epidemiology studies, two under peer review
  * Leads a pre/post impact evaluation of a carbon-emission reduction initiative
* **Research and Teaching Assistant**, Department of Statistics, FUTA, May 2024 – Dec 2025
* **Principal Data Analyst** (contract), Greenplinth Africa, Lagos, Apr 2025 – Sep 2025

Honours and Awards
======
* 1st Place, EGRA (eHealth Africa Group-wide Research Accelerator), inaugural round

Research Computing
======
* **Methods:** Bayesian computation (Stan/RStan, HMC/NUTS); likelihood approximation (collapsing, quadrature, particle filtering); GARCH-family, Markov-switching, and VAR/VECM models
* **Software:** R, Python, C++ (via Cython), SQL, EViews, Stata, LaTeX
* **Open source:** [PSTR-VECM](https://github.com/oluwadamilarejoshua/PSTRVEC), CIPS and Westerlund (2007) panel cointegration tests written from scratch in R

Presentations
======
<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>

Teaching
======
<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
