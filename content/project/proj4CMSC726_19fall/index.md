---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Cross-view Geo-localization"
summary: "In this project, we consider the problem of cross-view image-based ground-to-aerial
geo-localization: estimating the GPS location of a query ground view image by
finding corresponding matching images in an aerial/satellite view image database,
or vice versa. The major challenge is the radical change of viewpoint and different
light conditions as well as seasons. In our project, we examine recent studies in
deep-learning-based approaches for cross-view matching. Specifically, we train
and test these methods on a dataset collected on photorealistic simulator AirSim.
Other than working with panoramic ground view images and satellite imagery,
these methodologies are modified to work well with non-panoramic ground view
images and aerial images taken from smaller altitude. We also employ particle
filtering technique to accomplish the geo-localization task using the results from
cross-view image matching. We demonstrate the effectiveness of our methods with
intensive experiments."
authors: [[Deeksha Dixit](https://www.linkedin.com/in/d-dixit/), [Peihong Yu](https://peihongyu.com/), [Chen Chen](https://ccdtc.cc/)]
tags: [computer vision, cross-view]
categories: [Computer Vision]
date: 2019-12-15T19:31:15-05:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Smart"
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: "files/cvgl.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

In this project, we study randomized Singular Value Decomposition (SVD). Apart from the standard randomized SVD algorithm, two modified versions, one for eliminating the influence of the round-off error and one for adaptively determining the desired error threshold, are introduced and discussed. Their efficiency and stability are demonstrated by experiments on two test matrices, one is a given matrix that has full rank and slowly-decaying singular values and the other one is generated from the numerical solutions of a piece-wise constant diffusion equation. A special treatment when the input matrix is positive semi-definite is also discussed and validated with numerical results.
