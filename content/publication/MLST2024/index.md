---
title: "Towards Harmonization of SO(3)-Equivariance and Expressiveness:  a Hybrid Deep Learning Framework for Electronic-Structure Hamiltonian Prediction"
authors:
- Shi Yin
- Xinyang Pan
- admin
- ET AL
- Feng Wu
- Lixin He
author_notes:
- "Equal contribution"
- "Equal contribution"

date:  "2024-11-12T00:00:00Z"
doi: "https://doi.org/10.1088/2632-2153/ad8d30"

# Schedule page publish date 
publishDate: "2024-11-12T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Machine Learning: Science and Technology"
publication_short: ""

abstract: Deep learning for predicting the electronic-structure Hamiltonian of quantum systems necessitates satisfying the covariance laws, among which achieving SO(3)-equivariance without sacrificing the non-linear expressive capability of networks remains unsolved. To navigate the harmonization between SO(3)-equivariance and expressiveness, we propose HarmoSE, a deep learning method synergizing two distinct categories of neural mechanisms as a two-stage encoding and regression framework. The first stage corresponds to group theory-based neural mechanisms with inherent SO(3)-equivariant properties prior to the parameter learning process, while the second stage is characterized by a non-linear 3D graph Transformer network we propose, featuring high capability on non-linear expressiveness. Their combination lies in the point that, the first stage predicts baseline Hamiltonians with abundant SO(3)-equivariant features extracted, assisting the second stage in empirical learning of equivariance; and in turn, the second stage refines the first stage's output as a fine-grained prediction of Hamiltonians using powerful non-linear neural mappings, compensating for the intrinsic weakness on non-linear expressiveness capability of mechanisms in the first stage. Our method enables precise, generalizable predictions while capturing SO(3)-equivariance under rotational transformations, and achieves state-of-the-art performance in Hamiltonian prediction tasks under multiple Mean Absolute Error (MAE) metrics, such as the average MAE across all samples and matrix elements, the MAE for challenging samples, the MAE for different Hamiltonian blocks, and the MAE for the challenging blocks. It also demonstrates significant improvements in accuracy for downstream quantities, such as occupied orbital energy and the electronic wavefunction, as measured by MAE and cosine similarity, respectively.

# Summary. An optional shortened abstract.
summary: 

tags:
- Machine Learning
- AI For Science

# Display this page in the Featured widget?
featured: true

links:
- name: Link
  url: https://iopscience.iop.org/article/10.1088/2632-2153/ad8d30
url_pdf: https://iopscience.iop.org/article/10.1088/2632-2153/ad8d30
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
  caption: ''
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
