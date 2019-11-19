---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "ANOVA Gaussian process modeling for high-dimensional stochastic computational models"
authors:
date: 2019-11-13
doi:

# Schedule page publish date (NOT publication's date).
publishDate: 2019-11-13

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "In this paper we present a novel analysis of variance Gaussian process (ANOVA-GP) emulator for models governed by partial differential equations (PDEs) with high-dimensional random inputs. Gaussian process (GP) is a widely used surrogate modeling strategy, but it can become invalid when the inputs are high-dimensional. In this new ANOVA-GP strategy, high-dimensional inputs are decomposed into unions of local low-dimensional inputs, and principal component analysis (PCA) is applied to provide dimension reduction for each ANOVA term. We then systematically build local GP models for PCA coefficients based on ANOVA decomposition to provide an emulator for the overall high-dimensional problem. We present a general mathematical framework of ANOVA-GP, validate its accuracy and demonstrate its efficiency with numerical experiments."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: False

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/1911.05580.pdf
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
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
slides: ""
---
