---
title: "Multiple feature selection based on an optimization strategy for causal analysis of health data"
authors:
- R. Cong
- O. Deng
- S. Nishimura
- A. Ogihara
- Q. Jin
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
# date: "2025-02-27"
doi: "https://doi.org/10.1007/s13755-024-00312-8"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-11-12"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Health Information Science and Systems*, Vol. 12, No. 52"
publication_short: ""

abstract: Recent advancements in information technology and wearable devices have revolutionized healthcare through health data analysis. Identifying significant relationships in complex health data enhances healthcare and public health strategies. In health analytics, causal graphs are important for investigating the relationships among health features. However, they face challenges owing to the large number of features, complexity, and computational demands. Feature selection methods are useful for addressing these challenges. In this paper, we present a framework for multiple feature selection based on an optimization strategy for causal analysis of health data. We select multiple health features based on an optimization strategy. First, we define a Weighted Total Score (WTS) index to assess the feature importance after the combination of different feature selection methods. To explore an optimal set of weights for each method, we design a multiple feature selection algorithm integrated with the greedy algorithm. The features are then ranked according to their WTS, enabling selection of the most important ones. After that, causal graphs are constructed based on the selected features, and the statistical significance of the paths is assessed. Furthermore, evaluation experiments are conducted on an experiment dataset collected for this study and an open dataset for diabetes. The results demonstrate that our approach outperforms baseline models by reducing the number of features while improving model performance. Moreover, the statistical significance of the relationships between features uncovered through causal graphs is validated for both datasets. By using the proposed framework for multiple feature selection based on an optimization strategy for causal analysis, the number of features is reduced and the causal relationships are uncovered and validated.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Health Analytics
featured: true

# links:
# - name: ""
#   url: ""
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
