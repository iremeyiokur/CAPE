## CAPE 
Official PyTorch implementation of "CAPE: A CLIP-Aware Pointing Ensemble of Complementary Heatmap Cues for Embodied Reference Understanding" (**WACV 2026**). CAPE resolves referential ambiguity in cluttered scenes by fusing complementary pointing heatmaps with CLIP semantic guidance.

[![Paper](https://img.shields.io/badge/Paper-ArXiv-red.svg)](https://arxiv.org/pdf/2507.21888) 
[![Project Page](https://img.shields.io/badge/Project-Page-blue.svg)](https://iremeyiokur.github.io/CAPE_web/) 

---

## 📢 Updates
* **[Mar 2026]** Visit our poster: WACV 2026, March 9, Poster Session 3.
* **[Mar 2026]** Training code and evaluation scripts will be released soon.
* **[Nov 2025]** Paper accepted to WACV 2026.

## 💡 Abstract
Embodied Reference Understanding (ERU) is the task of identifying a specific object in a visual scene based on language instructions and human pointing cues. Previous methods rely heavily on the assumption that a target aligns perfectly with the head-to-fingertip direction. However, this "single-line assumption" fails when the user looks elsewhere, the scene is cluttered, or pointing is driven by the wrist. 

**CAPE** tackles this by moving beyond strict geometric assumptions. We propose a dual-model framework that fuses complementary **head-to-fingertip** and **wrist-to-fingertip** Gaussian ray heatmaps. These models are dynamically combined at inference time using a **CLIP-Aware Pointing Ensemble (CAPE)**, leveraging semantic similarity and a size-aware adaptation rule to achieve state-of-the-art robustness on datasets like YouRefIt, ISL Pointing, and CAESAR.

## 📖 Citation ##

```
@inproceedings{eyiokur2026cape,
  title={CAPE: A CLIP-Aware Pointing Ensemble of Complementary Heatmap Cues for Embodied Reference Understanding},
  author={Eyiokur, Fevziye Irem and Yaman, Dogucan and Ekenel, Haz{\i}m Kemal and Waibel, Alexander},
  booktitle={Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)},
  year={2026}
}
```

## 🙏 Acknowledgements
This work was supported in part by the European Union's Horizon research and innovation program, project Meetween (101135798) and project DVPS (Diversibus Viis Plurima Solvo) (101213369), and KIT Campus Transfer GmbH (KCT).

