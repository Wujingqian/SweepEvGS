# SweepEvGS: Event-Based 3D Gaussian Splatting for Macro and Micro Radiance Field Rendering from a Single Sweep

<p align="center">
  <img src="assets/intro2.png" width="700">
</p>

**Official repository for our IEEE TCSVT 2025 paper:**

> **"SweepEvGS: Event-Based 3D Gaussian Splatting for Macro and Micro Radiance Field Rendering from a Single Sweep"**  
> Jingqian Wu, Shuo Zhu, Chutian Wang, Boxin Shi, and Edmund Y. Lam  
> *IEEE Transactions on Circuits and Systems for Video Technology (TCSVT), 2025*  
> [[Paper on IEEE Xplore]](https://ieeexplore.ieee.org/document/11053840)

---

## 🧠 Overview

**SweepEvGS** is the first framework to reconstruct a complete 3D Gaussian Splatting (GS) radiance field from only a *single camera sweep*, combining a conventional frame and its accompanying event stream.  
It enables **robust macro- and micro-scale 3D radiance field rendering** with low latency and high fidelity.

Key features:
- **Single-Sweep Capture**: one blurry frame + dense event stream → full 3D GS representation  
- **Macro & Micro Unified Pipeline**: works seamlessly for large-scale and microscopic scenes  
- **Efficient Radiance Field Training**: fast convergence and lightweight storage  
- **Hardware-Integrated Setup**: compatible with event cameras and standard microscopes  

<p align="center">
  <img src="assets/pipline.png" width="750">
</p>

---

## 📦 Repository Contents

This repository currently contains:
