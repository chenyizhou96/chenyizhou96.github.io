---
title: "A Linear and Angular Momentum Conserving Hybrid Particle/Grid Iteration for Volumetric Elastic Contact"
authors:
- Alan Marquez Razon
- admin
- Yushan Han
- Steven Ganiere
- Michael Tupek
- Joseph Teran
author_notes:


# Schedule page publish date (NOT publication's date).
publishDate: "2023-08-24T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-conference"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the ACM on Computer Graphics and Interactive Techniques, Volume 6, Issue 3"
publication_short: ""

abstract: We present a momentum conserving hybrid particle/grid iteration for resolving volumetric elastic collision. Our hybrid method uses implicit time stepping with a Lagrangian finite element discretization of the volumetric elastic material together with impulse-based collision-correcting momentum updates designed to exactly conserve linear and angular momentum. We use a two-step process for collisions":" first we use a novel grid-based approach that leverages the favorable collision resolution properties of Particle-In-Cell (PIC) techniques, then we finalize with a classical collision impulse strategy utilizing continuous collision detection. Our PIC approach uses Affine-Particle-In-Cell momentum transfers as collision preventing impulses together with novel perfectly momentum conserving boundary resampling and downsampling operators that prevent artifacts in portions of the boundary where the grid resolution is of disparate resolution. We combine this with a momentum conserving augury iteration to remove numerical cohesion and model sliding friction. Our collision strategy has the same continuous collision detection as traditional approaches, however our hybrid particle/grid iteration drastically reduces the number iterations required. Lastly, we develop a novel symmetric positive semi-definite Rayleigh damping model that increases the convexity of the nonlinear systems associated with implicit time stepping. We demonstrate the robustness and efficiency of our approach in a number of collision intensive examples.


tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://dl.acm.org/doi/abs/10.1145/3606924


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
