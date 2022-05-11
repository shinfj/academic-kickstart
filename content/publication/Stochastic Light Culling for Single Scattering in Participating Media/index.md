---
title: "Stochastic Light Culling for Single Scattering in Participating Media"
authors:
- admin
- Yusuke Tokuyoshi
- Takahiro Harada
date: "2022-04-01"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-12-08T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In *Eurographics 2022 Short Papers*"
publication_short: "In *Eurographics 2022 Short Papers*"

abstract: We introduce a simple but efficient method to compute single scattering from point and arbitrarily shaped area light sources in participating media. Our method extends the stochastic light culling method to volume rendering by considering the intersection of a ray and spherical bounds of light influence ranges. For primary rays, this allows simple computation of the lighting in participating media without hierarchical data structures such as a light tree. First, we show how to combine equiangular sampling with the proposed light culling method in a simple case of point lights. We then apply it to arbitrarily shaped area lights by considering virtual point lights on the surface of area lights. Using our method, we are able to improve the rendering quality for scenes with many lights without tree construction and traversal.

# Summary. An optional shortened abstract.
summary:

tags:
featured: false

links:
- name: Supplemental
  url: 'https://www.dropbox.com/s/8jdj8xzvgn16os4/supplemental.pdf?dl=0'
- name: Publisher's official version
  url: 'https://diglib.eg.org/handle/10.2312/egs20221023'
url_pdf: 'https://www.dropbox.com/s/izyyrxzbqtqpl6w/paper.pdf?dl=0'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---
