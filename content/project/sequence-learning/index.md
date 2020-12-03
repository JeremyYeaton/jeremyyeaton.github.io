---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Statistical learning in noise
subtitle: 'Examining sequence learning in baboons'
summary: 'Examining sequence learning in baboons'
authors:
- Jeremy Yeaton
- Arnaud Rey
- Laure Tosatto
tags: []
categories: []
date: '2020-01-01'
lastmod: 2020-12-03T22:05:12+01:00
featured: true
draft: false
text:
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
publishDate: '2020-12-03T21:19:49.897724Z'
publication_types:
- '2'
---
In a series of experiments using a motor sequence learning task, we are examining the effect of different types of noise on the baboons' ability to extract a regularity (e.g.: AB) from a sequence. For example, if the baboon saw the pair AB 100 times, but each time it was in a different position in the sequence (e.g.: XABX, XXAB, ABXX, etc.), will that impede their ability to learn the relationship between A and B relative to if they only saw ABCD every trial?

In a parallel project, we are constructing a computational model of this learning process to better understand how the process takes place in baboons, and how that differs from in humans.
