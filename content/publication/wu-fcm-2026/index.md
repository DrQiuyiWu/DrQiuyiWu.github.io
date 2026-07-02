---
title: "Statistical Inference for Fuzzy Clustering"
authors:
- admin
- Zihan Zhu
- Anru Zhang


# Author notes (optional)
# author_notes:
#   - []
#   - 'Equal contribution'
#   - 'Equal contribution'



date: '2026-01-06'
# publishDate: '2024-02-05T04:51:17.658516Z'
publication_types:
- article-journal
# publication: "Advances in Statistical Climatology, Meteorology and Oceanography"
# publication_short: "ASCMO"
# doi: 10.5194/ascmo-8-205-2022

abstract: Clustering is a central tool in biomedical research for discovering heterogeneous patient subpopulations, where group boundaries are often diffuse rather than sharply separated. Traditional methods produce hard partitions, whereas soft clustering methods such as fuzzy $c$-means (FCM) allow mixed memberships and better capture uncertainty and gradual transitions. Despite the widespread use of FCM, principled statistical inference for fuzzy clustering remains limited. We develop a new framework for weighted fuzzy $c$-means (WFCM) for settings with potential cluster size imbalance. Cluster-specific weights rebalance the classical FCM criterion so that smaller clusters are not overwhelmed by dominant groups, and the weighted objective induces a normalized density model with scale parameter $\sigma$ and fuzziness parameter $m$. Estimation is performed via a blockwise majorize--minimize (MM) procedure that alternates closed-form membership and centroid updates with likelihood-based updates of $(\sigma,\bw)$. The intractable normalizing constant is approximated by importance sampling using a data-adaptive Gaussian mixture proposal. We further provide likelihood ratio tests for comparing cluster centers and bootstrap-based confidence intervals. We establish consistency and asymptotic normality of the maximum likelihood estimator, validate the method through simulations, and illustrate it using single-cell RNA-seq and Alzheimer disease Neuroimaging Initiative (ADNI) data. These applications demonstrate stable uncertainty quantification and biologically meaningful soft memberships, ranging from well-separated cell populations under imbalance to a graded AD versus non-AD continuum consistent with disease progression.

# Summary. An optional shortened abstract.
summary: We develop a likelihood-based weighted fuzzy c-means method for soft clustering under cluster imbalance, with consistent estimation, asymptotic normality, and valid inference. Its effectiveness is demonstrated in medical applications including single-cell RNA-seq and ADNI studies.



tags:
- Machine Learning
- Clustering Inference

# Display this page in the Featured widget?
featured: true


url_pdf: 'https://arxiv.org/abs/2601.02656'
url_code: 'https://github.com/QiuyiWu/WFCM'
#url_dataset: 'https://zenodo.org/records/6425797'

# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'
# - name: Slides
#   url: 'content/slides/example/SIAM_Wu.pdf'


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example


# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project



# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Wu et al.**]()'
  focal_point: ""
  preview_only: false
---
