---
title: Auto-STE
summary: Autonomous source term estimation using a UAV in cluttered, GPS denied environments.
tags:
  - Robotics
  - Autonomy
date: '2022-06-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: 'Autonomous source search'
  focal_point: Smart

links:
url_code: 'https://github.com/callum-rhodes/GADEN_industrial_env'
url_pdf: 'https://ieeexplore.ieee.org/document/9684970'
url_video: 'https://www.youtube.com/watch?v=_Sou67QbVqo&ab_channel=CunjiaLiu'

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Autonomous search for the source location of an airbourne chemical dispersion is performed entirely onboard a UAV within a GPS denied environment. SLAM output from a stereo camera is fed into the flight controller and a 3D octomap is used for collision free navigation. Information theoretic path planning is developed to guide future sensing locations by taking into account the uncertainty of the particle filter that is recursively estimating the parameters of the chemical dispersion.
