---
title: Parallel Hybrid (Cuda and MPI) implementation of Support Vector Machines (SVM)
summary: Parallel implementation of SVM with cascading using MPI and Sequential Mimimal Optimization (SMO) using Cuda.
tags:
- Machine Learning
- Parallel Programming
- Cuda
- MPI
- Distributed Computing
date: "2016-05-14T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: "Cascade SVM"
  focal_point: Smart

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: "https://github.com/imbesat-rizvi/SVM_Hybrid_Implementation_Cuda_and_MPI"
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Support Vector Machines (SVMs) are powerful but computationally expensive machine learning (ML) algorithm for supervised classification task which is frequently witnessed in the ML domain. For optimization of objective function SMO is widely used while for large dataset Cascading approach is well suited. Both of these are parallelizable in orthogonal sense i.e. independent of each other. Motivated by these, in this project, we have implemented a hybrid version of both the above mentioned techniques with SMO being implemented using CUDA while cascading being implemented using MPI.