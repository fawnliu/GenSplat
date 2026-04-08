<h1 align="center">GenSplat: Bridging the Generalization Gap in 3DGS Language Comprehension (CVPR 2026)</h1>

<p align="center">
  <a href="https://arxiv.org/abs/xxxx.xxxxx"><img src="https://img.shields.io/badge/arXiv-Paper-red?logo=arxiv&logoColor=white" /></a>
  <a href="https://fawnliu.github.io/project/gensplat/index.html"><img src="https://img.shields.io/badge/Project-Page-blue?logo=googlechrome&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/CVPR-2026-green" />
</p>

<p align="center">
  <a href="https://fawnliu.github.io/">Fang Liu</a><sup>*</sup>&nbsp;&nbsp;
  <a href="https://scholar.google.com/citations?user=eHWiGU8AAAAJ">Yuhao Liu</a><sup>*</sup>&nbsp;&nbsp;
  <a href="https://scholar.google.com/citations?user=2meBhbQAAAAJ">Ke Xu</a><sup>†</sup>&nbsp;&nbsp;
  <a href="https://scholar.google.com/citations?user=C2iR3xUAAAAJ">Gerhard Petrus Hancke</a>&nbsp;&nbsp;
  <a href="https://scholar.google.com/citations?user=KilQqKYAAAAJ">Rynson W.H. Lau</a><sup>†</sup>
</p>

<p align="center">
  City University of Hong Kong
</p>

<p align="center">
  <sup>*</sup>Equal Contribution&nbsp;&nbsp;&nbsp;<sup>†</sup>Corresponding Authors
</p>

## Abstract

Unlike previous methods that either achieve cross-scene generalization by being bounded to a predefined vocabulary or handle free-form language by overfitting to individual scenes, **GenSplat** is robust to free-form language queries and generalizable across 3DGS scene representations. Our key insight is to formulate a structured learning process to progressively align linguistic concepts with 3D Gaussians. It contains two novel technical contributions:
Progressive Language Grounding Curriculum that structurally guides the model through learning category-level semantics to instance-level concepts and free-form language, preventing overfitting by building a generalizable language feature space.
MLLM-guided Reasoning Module that leverages Multi-modal Large Language Models' semantic and spatial priors to enhance 3D localization and reasoning.
Extensive cross-task evaluations — including 3D referring segmentation, 3D visual question answering, and 3D open-vocabulary understanding — demonstrate state-of-the-art performances and strong generalization capability.

## Usage

Code will be released soon. Stay tuned!

## Citation

If you find this work useful, please consider citing:
<!-- 
```bibtex
@inproceedings{liu2026gensplat,
  title     = {GenSplat: Bridging the Generalization Gap in 3DGS Language Comprehension},
  author    = {Liu, Fang and Liu, Yuhao and Xu, Ke and Hancke, Gerhard Petrus and Lau, Rynson W.H.},
  booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
  year      = {2026}
}
``` -->

<!-- ## Acknowledgments

This work was supported by City University of Hong Kong. -->
<!-- 
## License

This project is released under the [Apache 2.0 License](LICENSE). -->
