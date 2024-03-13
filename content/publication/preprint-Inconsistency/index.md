---
title: "Inconsistency of evaluation metrics in link prediction"
authors:
- 毕祎琳
- 焦鑫善
- 李艳丽
- 周涛
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2024-03-10T00:00:00Z"
doi: "10.48550"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-02-14T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Link prediction is a paradigmatic and challenging problem in network science, which aims to predict missing links, future links and temporal links based on known topology. Along with the increasing number of link prediction algorithms, a critical yet previously ignored risk is that the evaluation metrics for algorithm performance are usually chosen at will. This paper implements extensive experiments on hundreds of real networks and 25 well-known algorithms, revealing significant inconsistency among evaluation metrics, namely different metrics probably produce remarkably different rankings of algorithms. Therefore, we conclude that any single metric cannot comprehensively or credibly evaluate algorithm performance. Further analysis suggests the usage of at least two metrics:one is the area under the receiver operating characteristic curve (AUC), and the other is one of the following three candidates, say the area under the precision-recall curve (AUPR), the area under the precision curve (AUC-Precision), and the normalized discounted cumulative gain (NDCG). In addition, as we have proved the essential equivalence of threshold-dependent metrics, if in a link prediction task, some specific thresholds are meaningful, we can consider any one threshold-dependent metric with those thresholds. This work completes a missing part in the landscape of link prediction, and provides a starting point toward a well-accepted criterion or standard to select proper evaluation metrics for link prediction. 

# Summary. An optional shortened abstract.
summary: link prediction, evaluation metrics, inconsistency

tags:
- 链路预测
featured: false

links:
- name: Arxiv链接
  url: https://arxiv.org/abs/2402.08893
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
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
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
slides: example
---
<!-- 
{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
