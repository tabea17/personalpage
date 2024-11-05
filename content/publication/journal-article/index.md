---
title: "Model-based clustering of multiple networks with a hierarchical algorithm"
authors:
- admin
date: "2024-09-01T00:00:00Z"
doi: "https://doi.org/10.1007/s11222-023-10329-w"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Statistics and Computing"
publication_short: ""

abstract: The paper tackles the problem of clustering multiple networks, directed or not, that do not share the same set of vertices, into groups of networks with similar topology. A statistical model-based approach based on a finite mixture of stochastic block models is proposed. A clustering is obtained by maximizing the integrated classification likelihood criterion. This is done by a hierarchical agglomerative algorithm, that starts from singleton clusters and successively merges clusters of networks. As such, a sequence of nested clusterings is computed that can be represented by a dendrogram providing valuable insights on the collection of networks. Using a Bayesian framework, model selection is performed in an automated way since the algorithm stops when the best number of clusters is attained. The algorithm is computationally efficient, when carefully implemented. The aggregation of clusters requires a means to overcome the label-switching problem of the stochastic block model and to match the block labels of the networks. To address this problem, a new tool is proposed based on a comparison of the graphons of the associated stochastic block models. The clustering approach is assessed on synthetic data. An application to a set of ecological networks illustrates the interpretability of the obtained results.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Source Themes
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/abs/2211.02314
url_code: 'https://cran.r-project.org/web/packages/graphclust/index.html'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
