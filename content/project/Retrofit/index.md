---
title: Retrofitting Word Vectors to Semantic Lexicons
summary: A vectorized iterative implementation of the paper "Retrofitting Word Vectors to Semantic Lexicons" in which the vector space representations are further refined using relational information from the semantic lexicons.
tags:
- Natural Language Processing
- Machine Learning
date: "2018-11-15T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: "Observed and inferred word vector representations (Faruqui et. al.)"
  focal_point: Smart

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: "https://github.com/imbesat-rizvi/retrofitting_vectors_to_semantic_lexicons"
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

A vectorized iterative implementation of the paper ["Retrofitting Word Vectors to Semantic Lexicons"](https://aclanthology.org/N15-1184.pdf) in which the vector space representations are further refined using relational information from the semantic lexicons. Word vectors are usually learned from distributional information of words in large corpora but they don't have valuable information that are contained in semantic lexicons such as WordNet, FrameNet and the Paraphrase Database. This implementation based on the source paper refines vector space representations using relational information from semantic lexicons by encouraging linked words to have similar vector representations, making no assumptions about how the input vectors were constructed.