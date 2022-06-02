---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Retrieve, Discriminate and Rewrite: A Simple and Effective Framework for Obtaining
  Affective Response in Retrieval-Based Chatbots'
subtitle: ''
summary: ''
authors:
- Xin Lu
- Yijian Tian
- Yanyan Zhao
- Bing Qin
tags: []
categories: []
date: '2021-11-01'
lastmod: 2022-06-01T19:58:59+08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-06-01T11:58:57.830320Z'
publication_types:
- '1'
abstract: Obtaining affective response is a key step in building empathetic dialogue
  systems. This task has been studied a lot in generation-based chatbots, but the
  related research in retrieval-based chatbots is still in the early stage. Existing
  works in retrieval-based chatbots are based on Retrieve-and-Rerank framework, which
  have a common problem of satisfying affect label at the expense of response quality.
  To address this problem, we propose a simple and effective Retrieve-Discriminate-Rewrite
  framework. The framework replaces the reranking mechanism with a new discriminate-and-rewrite
  mechanism, which predicts the affect label of the retrieved high-quality response
  via discrimination module and further rewrites the affect unsatisfied response via
  rewriting module. This can not only guarantee the quality of the response, but also
  satisfy the given affect label. In addition, another challenge for this line of
  research is the lack of an off-the-shelf affective response dataset. To address
  this problem and test our proposed framework, we annotate a Sentimental Douban Conversation
  Corpus based on the original Douban Conversation Corpus. Experimental results show
  that our proposed framework is effective and outperforms competitive baselines.
publication: '*Findings of the Association for Computational Linguistics: EMNLP 2021*'
doi: 10.18653/v1/2021.findings-emnlp.168
links:
- name: URL
  url: https://aclanthology.org/2021.findings-emnlp.168

url_pdf: https://aclanthology.org/2021.findings-emnlp.168.pdf
---
