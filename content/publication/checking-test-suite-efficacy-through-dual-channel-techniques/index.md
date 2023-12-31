---
title: Checking Test Suite Efficacy Through Dual-Channel Techniques
authors:
  - Constantin Cezar Petrescu
  - Sam Smith
  - Alexis Butler
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
draft: false
url_pdf: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4515283
publication_types:
  - "2"
publication: Journal
featured: true
tags:
  - Dual-channel Research
  - Software testing
  - Programme analysis
date: 2023-07-19T04:21:03.686Z
links: null
image:
  caption: ""
  focal_point: ""
  preview_only: false
publishDate: 2023-07-19T00:00:00Z
# url_code: https://github.com/Constantin-Petrescu/CastChecker
---
