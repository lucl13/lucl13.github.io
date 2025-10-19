---
layout: post
title: My favorite PyMOL settings
date: 2025-10-18 21:00:00
description: The PyMOL settings I always use for my figures, clean, soft, and publication ready
tags: PyMOL
categories: methods
chart:
  plotly: true
---

I often get asked how I generate the molecular graphics in my HX/MS and PIGEON-FEATHER papers. Here are my favorite PyMOL settings.

```python
# basic display settings
set cartoon_loop_radius, 0.4
set cartoon_sampling, 10
set cartoon_transparency, 0
set line_width, 3

# ray tracing settings
set ray_trace_mode, 1
set ray_shadows, 0
set ray_trace_gain, 0.1
set ray_trace_disco_factor, 1
set ray_trace_color, black

# lighting and material settings
set antialias, 2
set specular, 0
set power, 0.0
#set power, 0.2
set ambient, 0.4
set direct, 0.45
set valence, 0
# space cmyk
```

<img src="/assets/img/post/0001_pymol_example.png" width="400" alt="PIGEON-FEATHER">
