# Awesome Referring Remote Sensing Image Segmentation

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](https://github.com/Sixsheepdad/Awesome-Referring-Remote-Sensing-Image-Segmentation/pulls)

**Referring Remote Sensing Image Segmentation (RRSIS)** is a task that aims to segment specific objects or regions in remote sensing imagery based on natural language expressions. Unlike semantic segmentation which classifies all pixels into predefined categories, RRSIS allows users to flexibly describe targets of interest using free-form language, enabling more intuitive and fine-grained image interpretation. This task is particularly challenging in remote sensing due to large image scales, complex backgrounds, small and densely distributed objects, and varying orientations.

A curated list of papers and datasets for **Referring Remote Sensing Image Segmentation (RRSIS)**.

## Table of Contents

- [Papers](#papers)
- [Datasets](#datasets)

---

## Papers

| Paper | Source | Code |
| :--- | :---: | :---: |
| [Referring Image Segmentation for Remote Sensing Data](https://ieeexplore.ieee.org/document/10642726) | ![IGARSS](https://img.shields.io/badge/IGARSS-2024-orange) | - |
| [RRSIS: Referring Remote Sensing Image Segmentation](https://arxiv.org/abs/2306.08625) | ![TGRS](https://img.shields.io/badge/TGRS-2024-green) | [GitHub](https://github.com/zhu-xlab/rrsis) |
| [Rotated Multi-Scale Interaction Network for Referring Remote Sensing Image Segmentation](https://arxiv.org/abs/2312.12470) | ![CVPR](https://img.shields.io/badge/CVPR-2024-blue) | [GitHub](https://github.com/Lsan2401/RMSIN) |
| [Exploring Fine-Grained Image-Text Alignment for Referring Remote Sensing Image Segmentation](https://arxiv.org/abs/2409.13637) | ![TGRS](https://img.shields.io/badge/TGRS-2025-green) | [GitHub](https://github.com/Shaosifan/FIANet) |
| [RSRefSeg: Referring Remote Sensing Image Segmentation with Foundation Models](https://arxiv.org/abs/2501.06809) | ![arXiv](https://img.shields.io/badge/arXiv-2025-red) | [GitHub](https://github.com/KyanChen/RSRefSeg) |
| [RSRefSeg 2: Decoupling Referring Remote Sensing Image Segmentation With Foundation Models](https://arxiv.org/abs/2507.06231) | ![TGRS](https://img.shields.io/badge/TGRS-2025-green) | [GitHub](https://github.com/KyanChen/RSRefSeg2) |
| [RemoteSAM: Towards Segment Anything for Earth Observation](https://arxiv.org/abs/2505.18022) | ![ACM MM](https://img.shields.io/badge/ACM%20MM-2025-yellow) | [GitHub](https://github.com/1e12Leon/RemoteSAM) |
| [A Large-Scale Referring Remote Sensing Image Segmentation Dataset and Benchmark](https://arxiv.org/abs/2506.03583) | ![arXiv](https://img.shields.io/badge/arXiv-2025-red) | [GitHub](https://github.com/CVer-Yang/NWPU-Refer) |
| [Generalized Referring Expression Segmentation on Aerial Photos](https://arxiv.org/abs/2512.07338) | ![arXiv](https://img.shields.io/badge/arXiv-2025-red) | [Homepage](https://luispl77.github.io/aerial-d) |
| [RRSECS: Referring Remote Sensing Expression Comprehension and Segmentation](https://ieeexplore.ieee.org/document/11036256) | ![GRSM](https://img.shields.io/badge/GRSM-2025-purple) | - |
| [CroBIM-U: Uncertainty-Driven Referring Remote Sensing Image Segmentation](https://arxiv.org/abs/2601.03490) | ![TGRS](https://img.shields.io/badge/TGRS-2026-green) | - |
| [Hierarchical Textual-Visual Guidance for Referring Remote Sensing Segmentation](https://www.sciencedirect.com/science/article/abs/pii/S0031320326005455) | ![Pattern Recognition](https://img.shields.io/badge/Pattern%20Recognition-2026-blue) | - |
| [RIS-LAD: A Benchmark and Model for Referring Image Segmentation in Low-Altitude Drone Imagery](https://doi.org/10.1609/aaai.v40i14.38181) | ![AAAI](https://img.shields.io/badge/AAAI-2026-blue) | [GitHub](https://github.com/AHideoKuzeA/RIS-LAD-A-Benchmark-and-Model-for-Referring-Low-Altitude-Drone-Image-Segmentation) |

---

## Datasets

| Dataset | Paper | Year | Size | Link |
| :--- | :--- | :---: | :---: | :---: |
| RefSegRS | [RRSIS: Referring Remote Sensing Image Segmentation](https://arxiv.org/abs/2306.08625) | 2024 | 4,420 image-language-label triplets | [HuggingFace](https://huggingface.co/datasets/JessicaYuan/RefSegRS) (from [GitHub](https://github.com/zhu-xlab/rrsis)) |
| RRSIS-D | [Rotated Multi-Scale Interaction Network for Referring Remote Sensing Image Segmentation](https://arxiv.org/abs/2312.12470) | 2024 | 17,402 image-caption-mask triplets | [Google Drive](https://drive.google.com/drive/folders/1Xqi3Am2Vgm4a5tHqiV9tfaqKNovcuK3A) (from [GitHub](https://github.com/Lsan2401/RMSIN)) |
| NWPU-Refer | [A Large-Scale Referring Remote Sensing Image Segmentation Dataset and Benchmark](https://arxiv.org/abs/2506.03583) | 2025 | 15,003 images, 49,745 targets | [GitHub](https://github.com/CVer-Yang/NWPU-Refer) |
| RemoteSAM\_270K | [RemoteSAM: Towards Segment Anything for Earth Observation](https://arxiv.org/abs/2505.18022) | 2025 | 270K image-text-mask triplets | [HuggingFace](https://huggingface.co/datasets/1e12Leon/RemoteSAM270k) (from [GitHub](https://github.com/1e12Leon/RemoteSAM)) |
| RIS-LAD | [RIS-LAD: A Benchmark and Model for Referring Image Segmentation in Low-Altitude Drone Imagery](https://doi.org/10.1609/aaai.v40i14.38181) | 2026 | 13,871 image-text-mask triplets | [Google Drive](https://drive.google.com/file/d/1PmtaQH_F0AUoGWgpmDSpPu27E2XSdGd4/view) (from [GitHub](https://github.com/AHideoKuzeA/RIS-LAD-A-Benchmark-and-Model-for-Referring-Low-Altitude-Drone-Image-Segmentation)) |

---

## Contribution

Welcome contributions! If you find any missing papers or datasets, feel free to open an issue or submit a pull request.

## License

MIT
