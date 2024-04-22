---
title: U-ARE-ME
summary: Uncertainty aware rotation estimation in Manhattan environments.
tags:
  - Vision
  - Optimisation
  - Deep Learning
date: '2024-04-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: 'https://callum-rhodes.github.io/U-ARE-ME/'

image:
  caption: Real-time rotation estimation
  focal_point: Smart

links:
url_code: 'https://github.com/callum-rhodes/U-ARE-ME'
url_pdf: 'https://arxiv.org/pdf/2403.15583.pdf'
url_video: 'https://www.youtube.com/watch?v=Ze5xOGzLl7E&ab_channel=DysonRoboticsLaboratoryatImperialCollege'

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

- U-ARE-ME provides globally consistent rotation estimates in Manhattan environments across sequences of RGB images, without the need for camera intrinsics.
- This is done by finding the rotation matrix that aligns the predicted surface normals to the principal directions of the scene.
- Even in non-Manhattan scenes, it can reliably estimate the global up-direction (i.e. the pitch & roll).
