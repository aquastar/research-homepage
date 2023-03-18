---
title: "Explain Influence Maximization with Sobol Indices"
authors:
- Zonghan Zhang
- admin
date: "2023-04-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: SIAM International Conference on Data Mining 2023
publication_short: SDM

abstract: Due to its vast application on online social networks, Influence Maximization (IM) has garnered considerable attention over the last couple of decades. Current IM research lacks human-comprehensible explanations of how the seed set results in the influence effect, hence reducing the trustworthiness of existing solutions despite their applicability. Due to the intricacy of IM, the majority of current research concentrate on estimating first-order spreading power and often is regard the interplay between flows dispersed from different seeds. This study uses Sobol indices, the cornerstone of variance-based sensitivity analysis, to decompose the influence effect to individual seeds and their interactions. The Sobol indices are tailored for IM contexts by modeling the seed selection as binary variables. This explanation method is universally applicable to all network types, IM techniques, and diffusion models. Based on the explanation method, a general framework dubbed SobolIM is proposed to improve the performance of current IM studies by over-selecting nodes followed by an elimination strategy. Experiments on synthetic and real-world graphs demonstrate that the explanation of the impact effect can dependably identify the key high-order interaction between seeds across a variety of networks and IM methods. SobolIM is empirically proved to be superior on effectiveness and competitive on efficiency.

# Summary. An optional shortened abstract.
summary: A lightweigted model for modeling and utilizing higher-order relation in seeds.

tags:
- music
featured: true

#links:
#- name:
#  url:
url_pdf : "https://arxiv.org/abs/2207.07833"
url_code: 'https://github.com/oates9895/SIM/tree/main'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Higher-order relation in seeds'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
