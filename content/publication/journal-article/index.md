---
title: "A Robust Grid-Based Meshing Algorithm for Embedding Self-Intersecting Surfaces"
authors:
- Steven Gagniere
- Yushan Han
- admin
- David Hyde
- Alan Marquez-Razon
- Joseph Teran
- Ronald Fedkiw
author_notes:


# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-28T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Computer Graphics Forum"
publication_short: ""

abstract: The creation of a volumetric mesh representing the interior of an input polygonal mesh is a common requirement in graphics and computational mechanics applications. Most mesh creation techniques assume that the input surface is not self-intersecting. However, due to numerical and/or user error, input surfaces are commonly self-intersecting to some degree. The removal of self-intersection is a burdensome task that complicates workflow and generally slows down the process of creating simulation-ready digital assets. We present a method for the creation of a volumetric embedding hexahedron mesh from a self-intersecting input triangle mesh. Our method is designed for efficiency by minimizing use of computationally expensive exact/adaptive precision arithmetic. Although our approach allows for nearly no limit on the degree of self-intersection in the input surface, our focus is on efficiency in the most common case, which is many minimal self-intersections. The embedding hexahedron mesh is created from a uniform background grid and consists of hexahedron elements that are geometrical copies of grid cells. Multiple copies of a single grid cell are used to resolve regions of self-intersection/overlap. Lastly, we develop a novel topology-aware embedding mesh coarsening technique to allow for user-specified mesh resolution as well as a topology-aware tetrahedralization of the hexahedron mesh.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://onlinelibrary.wiley.com/doi/full/10.1111/cgf.14986


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

title: "A Robust Grid-Based Meshing Algorithm for Embedding Self-Intersecting Surfaces"
authors:
- Steven Gagniere
- Yushan Han
- admin
- David Hyde
- Alan Marquez-Razon
- Joseph Teran
- Ronald Fedkiw
author_notes:


# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-28T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Computer Graphics Forum"
publication_short: ""

abstract: The creation of a volumetric mesh representing the interior of an input polygonal mesh is a common requirement in graphics and computational mechanics applications. Most mesh creation techniques assume that the input surface is not self-intersecting. However, due to numerical and/or user error, input surfaces are commonly self-intersecting to some degree. The removal of self-intersection is a burdensome task that complicates workflow and generally slows down the process of creating simulation-ready digital assets. We present a method for the creation of a volumetric embedding hexahedron mesh from a self-intersecting input triangle mesh. Our method is designed for efficiency by minimizing use of computationally expensive exact/adaptive precision arithmetic. Although our approach allows for nearly no limit on the degree of self-intersection in the input surface, our focus is on efficiency in the most common case, which is many minimal self-intersections. The embedding hexahedron mesh is created from a uniform background grid and consists of hexahedron elements that are geometrical copies of grid cells. Multiple copies of a single grid cell are used to resolve regions of self-intersection/overlap. Lastly, we develop a novel topology-aware embedding mesh coarsening technique to allow for user-specified mesh resolution as well as a topology-aware tetrahedralization of the hexahedron mesh.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://onlinelibrary.wiley.com/doi/full/10.1111/cgf.14986


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



