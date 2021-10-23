---
title: "Identifying causal associations in tweets using deep learning: Use case on diabetes-related tweets from 2017-2021"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Adrian Ahne
- Vivek Khetan
- admin
- Xavier Tannier
- Thomas Czernichow
- Francisco Orchard
- Charline Bour
- Andrew Fano
- Guy Fagherazzi

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-10-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-10-05T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *Submission*
publication_short: In *Submission*

abstract: |

  **Objective** -- The amount of available health-related textual data is growing rapidly, urging the necessity of extracting the relevant information between entities: *cause-effect* relationships, to get a better understanding of health-related questions. Leveraging machine learning methods, we aim to extract both explicit and implicit multi-word *cause-effect* associations in diabetes-related tweets, where opinion, feelings and observations are expressed in real-time.

  **Materials and Methods** -- More than 30 million diabetes-related tweets in English were collected between April 2017 and January 2021. Deep learning and natural language processing methods were applied to focus on relevant tweets with personal and emotional content. A *cause-effect-tweet* dataset was manually labeled and used to train 1) a fine-tuned Bertweet model to detect *causal sentences* containing a causal association 2) a CRF model with BERT based features to extract possible cause-effect associations. Active learning was applied to augment the training data efficiently.

  **Results** -- We were able to detect *causal sentences* with an accuracy of 71% in an imbalanced dataset. A CRF model with BERT based features outperformed a fine-tuned BERT model for *cause-effect* detection with a macro F1 of 68%. This led to 96,676 tweets with cause-effect associations. “Diabetes” was identified as the central cluster followed by “Death” and “Insulin”. Insulin pricing related causes were frequently associated with “Death”.

  **Conclusions** -- A novel methodology was developed to tackle the challenging task of detecting causal sentences and identifying both explicit and implicit, single and multi-word cause as well as corresponding effect as expressed in diabetes-related tweets leveraging BERT-based architectures in combination with a manually labeled dataset augmented via active learning. Extracting causal associations on real-life, patient reported outcomes in social media data provides a useful complementary source of information in diabetes research.  


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: arXiv
#   url: https://arxiv.org/abs/2110.07090

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
