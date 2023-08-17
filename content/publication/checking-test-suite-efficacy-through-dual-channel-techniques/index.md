---
title: Checking Test Suite Efficacy Through Dual-Channel Techniques
authors:
  - Constantin Cezar Petrescu
  - Sam Smith
  - Rafail Giavrimis
  - Santanu Kumar Dash
publication_short: _SSRN 2023_
abstract: Dynamic Call Graphs trace program execution and are used to model
  function coverage. They help identify which function calls are missed but do
  not offer insights on whether those calls are important to cover. We propose a
  weighted representation of control flow called Natural Call Graphs (NCGs),
  which can be used to identify important function calls. These weights
  represent the relevance of the callee to the caller and are computed using
  information-theoretic reasoning on tokens in the functions. We create a
  dataset of 1,234 manually verified function calls, containing a mix of
  relevant and irrelevant functions, from ten Python open-source projects. On
  this dataset, our approach achieves a peak precision of 78% and a recall of
  94% in identifying relevant functions missed by tests.
draft: true
url_pdf: https://arxiv.org/pdf/2111.01577.pdf
publication_types:
  - "2"
url_source: https://doi.org/10.1016/j.jss.2023.111693
publication: Journal of Systems and Software
featured: true
tags:
  - C++ type conversions
  - Languages
  - Programme analysis
  - Dual-channel approach
date: 2023-08-17T04:21:03.686Z
links: null
image:
  caption: ""
  focal_point: ""
  preview_only: false
publishDate: 2023-04-6T00:00:00Z
url_code: https://github.com/Constantin-Petrescu/CastChecker
---
