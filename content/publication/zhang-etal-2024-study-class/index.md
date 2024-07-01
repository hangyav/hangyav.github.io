---
title: A Study of the Class Imbalance Problem in Abusive Language Detection
authors:
- Yaqi Zhang
- Viktor Hangya
- Alexander Fraser
date: '2024-06-01'
publishDate: '2024-07-01T18:10:31.488831Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 8th Workshop on Online Abuse and Harms (WOAH 2024)*'
abstract: 'Abusive language detection has drawn increasing interest in recent years.
  However, a less systematically explored obstacle is label imbalance, i.e., the amount
  of abusive data is much lower than non-abusive data, leading to performance issues.
  The aim of this work is to conduct a comprehensive comparative study of popular
  methods for addressing the class imbalance issue. We explore 10 well-known approaches
  on 8 datasets with distinct characteristics: binary or multi-class, moderately or
  largely imbalanced, focusing on various types of abuse, etc. Additionally, we pro-pose
  two novel methods specialized for abuse detection: AbusiveLexiconAug and ExternalDataAug,
  which enrich the training data using abusive lexicons and external abusive datasets,
  respectively. We conclude that: 1) our AbusiveLexiconAug approach, random oversampling,
  and focal loss are the most versatile methods on various datasets; 2) focal loss
  tends to yield peak model performance; 3) oversampling and focal loss provide promising
  results for binary datasets and small multi-class sets, while undersampling and
  weighted cross-entropy are more suitable for large multi-class sets; 4) most methods
  are sensitive to hyperparameters, yet our suggested choice of hyperparameters provides
  a good starting point.'
links:
- name: URL
  url: https://aclanthology.org/2024.woah-1.4
---
