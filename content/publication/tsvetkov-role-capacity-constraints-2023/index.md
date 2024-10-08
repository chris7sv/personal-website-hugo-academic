---
# Documentation: https://wowchemy.com/docs/managing-content/

title: The Role of Capacity Constraints in Convolutional Neural Networks for Learning
  Random versus Natural Data
subtitle: ''
summary: ''
authors:
- Christian Tsvetkov
- Gaurav Malhotra
- Benjamin D. Evans
- Jeffrey S. Bowers
tags:
- Biological constraints
- Bottleneck
- Capacity
- Deep Neural Networks
- Internal noise
categories: []
date: '2023-02-01'
lastmod: 2023-02-07T14:21:53Z
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
publishDate: '2023-02-07T14:20:27.804429Z'
publication_types:
- '2'
abstract: Convolutional neural networks (CNNs) are often described as promising models
  of human vision, yet they show many differences from human abilities. We focus on
  a superhuman capacity of top-performing CNNs, namely, their ability to learn very
  large datasets of random patterns. We verify that human learning on such tasks is
  extremely limited, even with few stimuli. We argue that the performance difference
  is due to CNNs' overcapacity and introduce biologically inspired mechanisms to constrain
  it, while retaining the good test set generalisation to structured images as characteristic
  of CNNs. We investigate the efficacy of adding noise to hidden units' activations,
  restricting early convolutional layers with a bottleneck, and using a bounded activation
  function. Internal noise was the most potent intervention and the only one which,
  by itself, could reduce random data performance in the tested models to chance levels.
  We also investigated whether networks with biologically inspired capacity constraints
  show improved generalisation to out-of-distribution stimuli, however little benefit
  was observed. Our results suggest that constraining networks with biologically motivated
  mechanisms paves the way for closer correspondence between network and human performance,
  but the few manipulations we have tested are only a small step towards that goal.
publication: '*Neural Networks*'
doi: 10.1016/j.neunet.2023.01.011
---
