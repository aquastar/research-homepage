---
title: "Graph Convolutional Networks with Kalman Filtering for Traffic Prediction"
authors:
- Fanglan Chen
- admin
- Subhodip Biswas
- Shuo Lei
- Naren Ramakrishnan
- Chang-Tien Lu


date: "2020-12-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-10-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication:  Proceedings of the 28th International Conference on Advances in Geographic Information 
publication_short: SIGSPATIAL

abstract: Traffic prediction is a challenging task due to the time-varying nature of traffic patterns and the complex spatial dependency of road networks. Adding to the challenge, there are a number of errors introduced in traffic sensor reporting, including bias and noise. However, most of the previous works treat the sensor observations as exact measures ignoring the effect of unknown noise. To model the spatial and temporal dependencies, existing studies combine graph neural networks (GNNs) with other deep learning techniques but their equal weighting of different dependencies limits the models' ability to capture the real dynamics in the traffic network. To deal with the above issues, we propose a novel deep learning framework called Deep Kalman Filtering Network (DKFN) to forecast the network-wide traffic state by modeling the self and neighbor dependencies as two streams, and their predictions are fused under the statistical theory and optimized through the Kalman filtering network. First, the reliability of each stream is evaluated using variances. Then, the Kalman filter is leveraged to properly fuse noisy observations in terms of their reliability. Experimental results reflect the superiority of the proposed method over baseline models on two real-world traffic datasets in the speed prediction task.


# Summary. An optional shortened abstract.
summary: Use Kalman filtering to handle uncertainty.

tags:
- clustering
featured: true

#links:
#- name:
#  url:  
url_pdf : "https://dl.acm.org/doi/10.1145/3397536.3422257"
url_code: 'https://github.com/Fanglanc/DKFN/tree/master'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.bilibili.com/video/BV1ea4y1L7Xo/'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'FusionGAN structure'
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
