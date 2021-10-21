---
abstract: In medical dialogue summarization, summaries must be coherent and must capture
  all the medically relevant information in the dialogue. However, learning effective
  models for summarization require large amounts of labeled data which is especially
  hard to obtain. We present an algorithm to create synthetic training data with an
  explicit focus on capturing medically relevant information. We utilize GPT-3 as
  the backbone of our algorithm and scale 210 human labeled examples to yield results
  comparable to using 6400 human labeled examples (∼30x) leveraging low-shot learning
  and an ensemble method. In detailed experiments, we show that this approach produces
  high quality training data that can further be combined with human labeled data
  to get summaries that are strongly preferable to those produced by models trained
  on human data alone both in terms of medical accuracy and coherency.
booktitle: Proceedings of the 6th Machine Learning for Healthcare Conference
title: Medically Aware GPT-3 as a Data Generator for Medical Dialogue Summarization
volume: '149'
year: '2021'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chintagunta21a
month: 0
tex_title: Medically Aware GPT-3 as a Data Generator for Medical Dialogue Summarization
firstpage: 354
lastpage: 372
page: 354-372
order: 354
cycles: false
bibtex_author: Chintagunta, Bharath and Katariya, Namit and Amatriain, Xavier and
  Kannan, Anitha
author:
- given: Bharath
  family: Chintagunta
- given: Namit
  family: Katariya
- given: Xavier
  family: Amatriain
- given: Anitha
  family: Kannan
date: 2021-10-21
address:
container-title: Proceedings of the 6th Machine Learning for Healthcare Conference
genre: inproceedings
issued:
  date-parts:
  - 2021
  - 10
  - 21
pdf: https://proceedings.mlr.press/v149/chintagunta21a/chintagunta21a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
