---
title: "Precise Surface Profiling at the Nanoscale Enabled by Deep Learning"
authors:
- Lalith Krishna Samanth Bonagiri
- admin
- Shan Zhou
- Yingjie Zhang
date: "2024-01-22"
doi: "https://doi.org/10.1021/acs.nanolett.3c04712"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-22"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Nano Letters"
publication_short: "Nano Lett. 2024, 24, 8, 2589–2595"

abstract: |
  Surface topography, or height profile, is a critical property for various micro- and nanostructured materials and devices, as well as biological systems. At the nanoscale, atomic force microscopy (AFM) is the tool of choice for surface profiling due to its capability to noninvasively map the topography of almost all types of samples. However, this method suffers from one drawback: the convolution of the nanoprobe’s shape in the height profile of the samples, which is especially severe for sharp protrusion features. Here, we report a deep learning (DL) approach to overcome this limit. Adopting an image-to-image translation methodology, we use data sets of tip-convoluted and deconvoluted image pairs to train an encoder–decoder based deep convolutional neural network. The trained network successfully removes the tip convolution from AFM topographic images of various nanocorrugated surfaces and recovers the true, precise 3D height profiles of these samples.

# Summary. An optional shortened abstract.
summary: |
  An encoder-decoder based deep convolutional neural network for enhancing the resolution of nanoscale profilometry.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://doi.org/10.1021/acs.nanolett.3c04712

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Nano Letters**](https://pubs.acs.org/cms/10.1021/acs.nanolett.3c04712/asset/images/medium/nl3c04712_0005.gif)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
---