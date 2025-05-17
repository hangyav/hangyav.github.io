---
title: Fine-Grained Transfer Learning for Harmful Content Detection through Label-Specific
  Soft Prompt Tuning
authors:
- Faeze Ghorbanpour
- Viktor Hangya
- Alexander Fraser
date: '2025-04-01'
publishDate: '2025-05-17T06:13:34.518177Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 2025 Conference of the Nations of the Americas Chapter
  of the Association for Computational Linguistics: Human Language Technologies (Volume
  1: Long Papers)*'
abstract: 'The spread of harmful content online is a dynamic issue evolving over time.
  Existing detection models, reliant on static data, are becoming less effective and
  generalizable. Developing new models requires sufficient up-to-date data, which
  is challenging. A potential solution is to combine existing datasets with minimal
  new data. However, detection tasks vary---some focus on hate speech, offensive,
  or abusive content, which differ in the intent to harm, while others focus on identifying
  targets of harmful speech such as racism, sexism, etc.---raising the challenge of
  handling nuanced class differences. To address these issues, we introduce a novel
  transfer learning method that leverages class-specific knowledge to enhance harmful
  content detection. In our approach, we first present label-specific soft prompt
  tuning, which captures and represents class-level information. Secondly, we propose
  two approaches to transfer this fine-grained knowledge from source (existing tasks)
  to target (unseen and new tasks): initializing the target task prompts from source
  prompts and using an attention mechanism that learns and adjusts attention scores
  to utilize the most relevant information from source prompts. Experiments demonstrate
  significant improvements in harmful content detection across English and German
  datasets, highlighting the effectiveness of label-specific representations and knowledge
  transfer.'
links:
- name: URL
  url: https://aclanthology.org/2025.naacl-long.551/
---
