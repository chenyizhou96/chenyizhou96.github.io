---
title: "Primal Extended Position Based Dynamics for Hyperelasticity"
authors:
- admin
- Yushan Han
- Jingyu Chen
- Shiqian Ma
- Ronald Fedkiw
- Joseph Teran
author_notes:


# Schedule page publish date (NOT publication's date).
publishDate: "2023-11-15T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-conference"]

# Publication name and optional abbreviated publication name.
publication: "MIG '23: Proceedings of the 16th ACM SIGGRAPH Conference on Motion, Interaction and Games"
publication_short: ""

abstract: The Extended Position Based Dynamics (XPBD) approach of Macklin et al. [2016] addresses the issues with iteration-dependent behavior in the original Position Based Dynamics [2007] (PBD) which itself is a powerful method for the real-time simulation of elastic objects. However, it is limited in its application to hyperelastic solids. It can only treat models with a strain energy density that is quadratic in some notion of constraint. Furthermore, we show that even when applicable the formulation does not always lead to convergent behaviors with hyperelasticity. We isolate the root cause in the approximate linearization of the nonlinear backward Euler systems utilized by XPBD. We provide two fixes to these terms that allow for convergent behavior. The first (B-PXPBD) is a small modification to an existing XPBD code, but can only be used with models addressable by the original XPBD. The second (FP-PXPBD) is a more general formulation that extends XPBD (and our residual correction) to arbitrary hyperelasticity. We show that our modifications allow for convergent behavior that rivals accurate techniques like Newton’s method when the computational budget is large without sacrificing the stable and robust behavior exhibited by the original PBD and XPBD when the computational budget is limited.


tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://dl.acm.org/doi/10.1145/3623264.3624437

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


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
---

