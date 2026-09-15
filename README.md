<div align="center">
<h1>G-ray: Ray-Level Relative Geometric Position Encoding in Multi-View Visual Transformers under Camera Heterogeneity</h1>

<a href="https://g-ray-project.github.io/"><img src="https://img.shields.io/badge/Project_Page-green" alt="Project Page"></a>

**[Wuhan University](https://www.whu.edu.cn/)**; **[Institute of Automation, Chinese Academy of Sciences](http://www.ia.cas.cn/)** and **[Wuhan AI Research](https://www.wair.ac.cn/)**; **Rongyun Robot (Guizhou) Co., Ltd.**

Shuo Zhang, Xin Su, Wei Wang, Jun Liu, Xinrui Zeng, Yongsen Chen, Chenjie Wang, Guibo Zhu, Jinqiao Wang, Bin Luo<sup>&dagger;</sup>, Liangpei Zhang

<sup>&dagger;</sup> Corresponding author

<a href="https://arxiv.org/abs/2609.15018"><img src="https://img.shields.io/badge/arXiv-2609.15018-b31b1b" alt="arXiv"></a>

</div>

```bibtex
@article{zhang2026gray,
  title={G-ray: Ray-Level Relative Geometric Position Encoding in Multi-View Visual Transformers under Camera Heterogeneity},
  author={Zhang, Shuo and Su, Xin and Wang, Wei and Liu, Jun and Zeng, Xinrui and Chen, Yongsen and Wang, Chenjie and Zhu, Guibo and Wang, Jinqiao and Luo, Bin and Zhang, Liangpei},
  year={2026}
}
```

## Updates

- [Sep 14, 2026] Project page is online at [https://g-ray-project.github.io/](https://g-ray-project.github.io/). Code will be released here.

## Overview

**G-ray** is a ray-level relative position encoding for multi-view visual Transformers under camera heterogeneity, including varying fields of view (FoVs) or projection models.

Existing rotary relative position encodings commonly use image-plane positional coordinates, which produce projection-dependent relative phases. G-ray instead parameterizes rotary phases with **camera-local ray angles**, so the same camera-local ray pair induces the same relative phase across projections. It can be used directly or integrated with existing encodings such as RoPE, GTA, and RayRoPE, without additional learned parameters.

<p align="center">
  <img src="assets/figure_1.png" alt="Overview of G-ray under camera heterogeneity, with 3D reconstruction and novel-view synthesis examples." width="92%"/>
</p>

## Code Release

**Code will be coming soon.**

This repository will host the implementation of G-ray, including integration with host encodings for 3D reconstruction and novel-view synthesis.

## Checklist

- [ ] Release the code
- [ ] Release pretrained checkpoints
- [ ] Release evaluation scripts

## Acknowledgements

This work was supported by the National Key R&D Program of China under Grants 2022ZD0160601 and 2022YFB3903404.

The project page is adapted from [RayRoPE](https://rayrope.github.io/) and [Nerfies](https://github.com/nerfies/nerfies.github.io).
