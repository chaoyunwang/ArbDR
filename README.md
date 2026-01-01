# ArbDR

## Cascaded Robust Rectification for Arbitrary Document Images

[![IEEE TMM](https://img.shields.io/badge/IEEE%20TMM-Accepted-success.svg)](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=6046)
[![arXiv](https://img.shields.io/badge/arXiv-2511.23150-b31b1b.svg)](https://arxiv.org/abs/2511.23150)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)

**Official implementation of "Cascaded Robust Rectification for Arbitrary Document Images"**

**Accepted by IEEE Transactions on Multimedia (TMM) 2026** 🏆

> **Authors:** Chaoyun Wang, Quanxin Huang, I-Chao Shen, Takeo Igarashi, Nanning Zheng, Caigui Jiang

> **Institutes:** Xi'an Jiaotong University, The University of Tokyo

---

### 📢 News

* **[2026.01.01]** 🎉 Our paper has been accepted by **IEEE Transactions on Multimedia (TMM)**!
* **[Update]** Code is being organized and will be fully released soon.

### 🚀 Introduction

Document rectification in real-world scenarios poses significant challenges due to extreme variations in camera perspectives and physical distortions. Driven by the insight that complex transformations can be decomposed and resolved progressively, we introduce a novel multi-stage framework that progressively reverses distinct distortion types in a coarse-to-fine manner. Specifically, our framework first performs a global affine transformation to correct perspective distortions arising from the camera's viewpoint, then rectifies geometric deformations resulting from physical paper curling and folding, and finally employs a content-aware iterative process to eliminate fine-grained content distortions. To address limitations in existing evaluation protocols, we also propose two enhanced metrics: layout-aligned OCR metrics (AED/ACER) for a stable assessment that decouples geometric rectification quality from the layout analysis errors of OCR engines, and masked AD/AAD (AD-M/AAD-M) tailored for accurately evaluating geometric distortions in documents with incomplete boundaries. Extensive experiments show that our method establishes new state-of-the-art performance on multiple challenging benchmarks, yielding a substantial reduction of 14.1\%--34.7\% in the AAD metric and demonstrating superior efficacy in real-world applications. 

### 📝 Citation

If you find our work useful in your research, please consider citing:

```bibtex
@article{wang2025cascaded,
  title={Cascaded Robust Rectification for Arbitrary Document Images},
  author={Wang, Chaoyun and Huang, Quanxin and Shen, I and Igarashi, Takeo and Zheng, Nanning and Jiang, Caigui and others},
  journal={arXiv preprint arXiv:2511.23150},
  year={2025}
}
```
