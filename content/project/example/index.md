---
title: Bin Optimized Motion Planning
summary: Motion planning in cluttered bins intended for warehouse use.
tags:
  - Robotics
  - Motion Planning
  - Deep Learning
date: '2023-09-23T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: 'https://sites.google.com/berkeley.edu/
bomp'

image:
  caption: Splash figure
  focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
# url_code: ''
# url_pdf: ''
# url_slides: ''
# url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

In automated warehouses, the ability to quickly
compute and execute pick-and-place motions is critical to
increasing productivity. In this paper, we present Bin-Optimized
Motion Planning (BOMP), a motion planning framework that
considers kinematics, actuation limits, the dimensions of a
grasped box, and a varying depth map of a bin environ-
ment, to rapidly generate time-optimized, jerk-limited and
collision-free trajectories. Experiments in 150 simulated and
physical environments suggest that BOMP generates collision-
free trajectories that are up to 44% and 26% faster than
a baseline sampling-based planner and a Cartesian heuristic
control algorithm, respectively. Furthermore, BOMP generates
jerk-limited trajectories while baselines do not. See https://
sites.google.com/berkeley.edu/bomp for code, video
and datasets