---
title: "Position-Based Nonlinear Gauss-Seidel for Quasistatic Hyperelasticity"
authors:
- admin
- Yushan Han
- Jingyu Chen
- Joseph Teran
author_notes:


# Schedule page publish date (NOT publication's date).
publishDate: "2023-06-15T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-preprint"]

# Publication name and optional abbreviated publication name.
publication: "Arxiv Preprint"
publication_short: ""

abstract: Position based dynamics is a powerful technique for simulating a variety of materials. Its primary strength is its robustness when run with limited computational budget. We develop a novel approach to address problems with PBD for quasistatic hyperelastic materials. Even though PBD is based on the projection of static constraints, PBD is best suited for dynamic simulations. This is particularly relevant since the efficient creation of large data sets of plausible, but not necessarily accurate elastic equilibria is of increasing importance with the emergence of quasistatic neural networks. Furthermore, PBD projects one constraint at a time. We show that ignoring the effects of neighboring constraints limits its convergence and stability properties. Recent works have shown that PBD can be related to the Gauss-Seidel approximation of a Lagrange multiplier formulation of backward Euler time stepping, where each constraint is solved/projected independently of the others in an iterative fashion. We show that a position-based, rather than constraint-based nonlinear Gauss-Seidel approach solves these problems. Our approach retains the essential PBD feature of stable behavior with constrained computational budgets, but also allows for convergent behavior with expanded budgets. We demonstrate the efficacy of our method on a variety of representative hyperelastic problems and show that both successive over relaxation (SOR) and Chebyshev acceleration can be easily applied.


tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/abs/2306.09021

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

