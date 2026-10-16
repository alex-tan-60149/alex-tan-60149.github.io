---
title: "TileGS: Tile-Local Depth Binning for Gaussian Splatting Rasterization"
collection: publications
category: conferences
permalink: /publication/2026-tilegs
date: 2026-10-01
venue: "Pacific Graphics 2026, Conference Track"

paperurl: "https://arxiv.org/abs/2609.03613"
doiurl: "https://doi.org/10.2312/pg.20261013"
videourl: "https://www.youtube.com/watch?v=qWZpB10j0BU"
codeurl: ""

excerpt: "Tile-local depth binning for efficient Gaussian splatting rasterization."
---

**Wei Tan**, Matias Turkulainen, Lauri Ilola, Hamed Rezazadegan Tavakoli, and Juho Kannala

*Pacific Graphics 2026, Conference Track*

TileGS reorganizes Gaussian splatting rasterization into tile-local depth bins while preserving the Gaussian representation and compositing semantics. The method reduces effective raster traversal work and improves rasterization efficiency across the evaluated scenes and GPUs.

## Links

[Paper](https://arxiv.org/abs/2609.03613) ·
[DOI](https://doi.org/10.2312/pg.20261013) ·
[Video](https://www.youtube.com/watch?v=qWZpB10j0BU)

## Abstract

TileGS introduces a tile-local depth-binning pipeline for Gaussian Splatting rasterization. Instead of changing the Gaussian representation or compositing rules, it reorganizes the same Gaussian-tile workload into front-to-back depth-local bins within each tile.

This traversal reorganization reduces effective raster work by allowing pixels to reach early termination after fewer Gaussian tests, while selective local repair preserves baseline-equivalent rendering quality.

Across a nine-scene benchmark, TileGS achieves consistent rasterization speedups while maintaining negligible quality differences relative to the gsplat baseline.

## Citation

Wei Tan, Matias Turkulainen, Lauri Ilola, Hamed Rezazadegan Tavakoli, and Juho Kannala.  
**TileGS: Tile-Local Depth Binning for Gaussian Splatting Rasterization.**  
Pacific Graphics 2026.
