---
layout: post
title: PFNet Viewer
date: 2026-02-11 12:00:00
description: A VSCode extension for interactive visualization of PDB files from PFNet predictions
tags: code
categories: methods
---

I made a VSCode extension that allows you to visualize PDB files from [PFNet](https://github.com/glasgowlab/PFNet) directly in your VSCode, replicating the same interactive experience as the Gradio interface. This means you no longer need to re-run the entire prediction pipeline just to perform interactive analysis on your results.

You can easily find it in the VSCode extension marketplace by searching "PFNet Viewer". This is a modified fork of the original [Protein Viewer](https://marketplace.visualstudio.com/items?itemName=ArianJamasb.protein-viewer) by Arian Jamasb, with several small adaptations to visualize ΔGop and ΔΔGop values from PFNet.

Right-click on a ΔGop/ΔΔGop PDB file to open the viewer. Hover over a residue to see the ΔGop/ΔΔGop value along with its confidence, and click on a residue to display its interactions.

<!-- <img src="/assets/img/post/PFNet_viewer1.png" width="400" alt="PFNet Viewer"> -->
<img src="/assets/img/post/PFNet_viewer2.png" width="600" alt="PFNet Viewer">
