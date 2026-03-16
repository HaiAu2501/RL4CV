<div align="center">

# 🎯 RL4CV  
### Reinforcement Learning for Computer Vision

📚 A curated collection of papers exploring the intersection of  
**Reinforcement Learning × Computer Vision**

<p>

<img src="https://img.shields.io/github/stars/HaiAu2501/RL4CV?style=social">
<img src="https://img.shields.io/github/forks/HaiAu2501/RL4CV?style=social">
<img src="https://img.shields.io/github/last-commit/HaiAu2501/RL4CV">
<img src="https://img.shields.io/badge/Papers-RL%20%2B%20Vision-blue">
<img src="https://img.shields.io/badge/Contributions-Welcome-brightgreen">

</p>

</div>

---

## 📖 Overview

This repository is a curated **awesome list** of research papers at the intersection of **Reinforcement Learning (RL)** and **Computer Vision (CV)**, sourced from top-tier A\* conferences including **CVPR**, **ICCV**, **ECCV**, **NeurIPS**, **ICML**, **ICLR**, **ICRA**, **AAAI**, and **IJCAI**.

Papers are organized by CV task to help researchers quickly navigate the rapidly evolving landscape.

> [!NOTE]
> RL4CV denotes methods where reinforcement learning is applied to support or improve computer vision tasks and vision pipelines.

> **Available Tags**: 
> * Highly Cited ⭐
> * Benchmarks & Datasets 📊

--- 

## 📂 Topics

- [1. Object Detection & Localization](#1-object-detection--localization)
- [2. Image Segmentation](#2-image-segmentation)
- [3. Image & Video Generation](#3-image--video-generation)
- [4. Video Understanding & Reasoning](#4-video-understanding--reasoning)
- [5. Image Restoration & Enhancement](#5-image-restoration--enhancement)
- [6. 3D Vision & View Planning](#6-3d-vision--view-planning)
- [7. Medical Image Analysis](#7-medical-image-analysis)
- [8. Visual Navigation & Embodied AI](#8-visual-navigation--embodied-ai)
- [9. Vision-Language Models with RL](#9-vision-language-models-with-rl)

---

### 1. Object Detection & Localization

> RL agents sequentially search, zoom, and localize objects in images.

| Paper | Venue | Year | Links |
|-------|-------|------|-------|
| **Recurrent Models of Visual Attention** ⭐ | NeurIPS | 2014 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/1406.6247) |
| **Multiple Object Recognition with Visual Attention** ⭐ | ICLR | 2015 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/1412.7755) |
| **Active Object Localization with Deep Reinforcement Learning** ⭐ | ICCV | 2015 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/1511.06015) |
| **Hierarchical Object Detection with Deep Reinforcement Learning** | NeurIPS DRL Workshop | 2016 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/1611.03718) |
| **Tree-Structured Reinforcement Learning for Sequential Object Localization** | NeurIPS | 2016 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/1703.02710) |
| **Reinforcement Learning for Visual Object Detection** ⭐ | CVPR | 2016 | [![Paper](https://img.shields.io/badge/Paper-red)](https://openaccess.thecvf.com/content_cvpr_2016/papers/Mathe_Reinforcement_Learning_for_CVPR_2016_paper.pdf) |
| **Attend Refine Repeat: Active Box Proposal Generation via In-Out Localization** | BMVC | 2016 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/1606.04446) |
| **Efficient Object Detection in Large Images using Deep Reinforcement Learning** | WACV | 2020 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/1912.03966) |
| **Learning to View: Decision Transformers for Active Object Detection** | ICRA | 2023 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/2301.09544) |
| **Reward Finetuning for Faster and More Accurate Unsupervised Object Discovery** | NeurIPS | 2023 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/2310.19080) |
| **Adaptive Important Region Selection with Reinforced Hierarchical Search for Dense Object Detection** | NeurIPS | 2024 | [![Paper](https://img.shields.io/badge/Paper-red)](https://neurips.cc/virtual/2024/poster/94227) |
| **Action-Decision Networks for Visual Tracking with Deep Reinforcement Learning** ⭐ | CVPR | 2017 | [![Paper](https://img.shields.io/badge/Paper-red)](https://openaccess.thecvf.com/content_cvpr_2017/html/Yun_Action-Decision_Networks_for_CVPR_2017_paper.html) |
| **AutoAugment: Learning Augmentation Strategies from Data** ⭐ | CVPR | 2019 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/1805.09501) |
| **A2-RL: Aesthetics Aware Reinforcement Learning for Image Cropping** | CVPR | 2018 | [![Paper](https://img.shields.io/badge/Paper-red)](https://openaccess.thecvf.com/content_cvpr_2018/html/Li_A2-RL_Aesthetics_Aware_CVPR_2018_paper.html) |


---

### 2. Image Segmentation

> RL for interactive, sequential, or region-growing segmentation strategies.

| Paper | Venue | Year | Links |
|-------|-------|------|-------|
| **Reinforced Active Learning for Image Segmentation** ⭐ | ICLR | 2020 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/2002.06583) |
| **Embodied Visual Active Learning for Semantic Segmentation** | AAAI | 2021 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/2012.09503) |
| **AlignSAM: Aligning Segment Anything Model to Open Context via Reinforcement Learning** | CVPR | 2024 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/2406.00480) |
| **Focus-Then-Decide: Segmentation-Assisted Reinforcement Learning** | AAAI | 2024 | [![Paper](https://img.shields.io/badge/Paper-red)](https://ojs.aaai.org/index.php/AAAI/article/view/29002) |
| **SAM-R1: Leveraging SAM for Reward Feedback in Multimodal Segmentation via Reinforcement Learning** | NeurIPS | 2025 | [![Paper](https://img.shields.io/badge/Paper-red)](https://openreview.net/forum?id=dHOSTp8MBl) |
| **Seg-Zero: Reasoning-Chain Guided Segmentation via Cognitive Reinforcement** | arXiv | 2025 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/2503.06520) |

---

### 3. Image & Video Generation

> Aligning visual generative models with human preferences via RL fine-tuning.

| Paper | Venue | Year | Links |
|-------|-------|------|-------|
| **ImageReward: Learning and Evaluating Human Preferences for Text-to-Image Generation** | NeurIPS | 2023 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/2304.05977) |
| **DPOK: Reinforcement Learning for Fine-tuning Text-to-Image Diffusion Models** | NeurIPS | 2023 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/2305.16381) |
| **Training Diffusion Models with Reinforcement Learning** ⭐ | ICLR | 2024 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/2305.13301) |
| **RAFT: Reward rAnked FineTuning for Generative Foundation Model Alignment** | TMLR | 2024 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/2304.06767) |
| **Rich Human Feedback for Text-to-Image Generation** | CVPR | 2024 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/2312.10240) |
| **Diff-Instruct++: Training One-step Text-to-image Generator Model to Align with Human Preferences** | TMLR | 2024 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2410.18881) |
| **Training Diffusion Models Towards Diverse Image Generation with Reinforcement Learning** | CVPR | 2024 | [![Paper](https://img.shields.io/badge/Paper-red)](https://openaccess.thecvf.com/content/CVPR2024/html/Miao_Training_Diffusion_Models_Towards_Diverse_Image_Generation_with_Reinforcement_Learning_CVPR_2024_paper.html) |
| **AlignProp: Aligning Diffusion Models by Backpropagating to Prompts** | ICLR | 2024 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/2310.03739) |
| **RLVLM-F: Reinforcement Learning from Vision-Language Model Feedback for Image Generation** | ICLR | 2024 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/2402.01176) |

---

### 4. Video Understanding & Reasoning

> RL for long-horizon temporal reasoning, highlight detection, and video summarization.

| Paper | Venue | Year | Links |
|-------|-------|------|-------|
| **End-to-end Learning of Action Detection from Frame Glimpses in Videos** | CVPR | 2016 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/1511.06984) |
| **Reinforced Video Captioning with Entailment Rewards** | EMNLP | 2017 | [![Paper](https://img.shields.io/badge/Paper-red)](https://aclanthology.org/D17-1103/) |
| **Self-Critical Sequence Training for Image Captioning** ⭐ | CVPR | 2017 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/1612.00563) |
| **Deep Reinforcement Learning for Unsupervised Video Summarization with Diversity-Representativeness Reward** ⭐ | AAAI | 2018 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/1801.00054) |
| **Video Captioning via Hierarchical Reinforcement Learning** | CVPR | 2018 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/1711.11135) |
| **Reinforcement Cutting-Agent Learning for Video Object Segmentation** | CVPR | 2018 | [![Paper](https://img.shields.io/badge/Paper-red)](https://openaccess.thecvf.com/content_cvpr_2018/papers/Han_Reinforcement_Cutting-Agent_Learning_CVPR_2018_paper.pdf) |
| **AdaFocus: Adaptive Focus for Efficient Video Recognition** | ICCV | 2021 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/2105.03245) |
| **Scaling RL to Long Videos** | NeurIPS | 2025 | [![Paper](https://img.shields.io/badge/Paper-red)](https://openreview.net/forum?id=TxedB8hI5O) |
| **Video-R1: Reinforcing Video Reasoning in MLLMs** | NeurIPS | 2025 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/2503.21776) |
| **SCSampler: Sampling Salient Clips from Video for Efficient Action Recognition** | ICCV | 2019 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/1904.04289) |
| **AdaFocus V2: End-to-End Training of Spatial Dynamic Networks for Video Recognition** | CVPR | 2022 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/2112.14238) |

---

### 5. Image Restoration & Enhancement

> RL for adaptive, step-wise image denoising, super-resolution, and retouching.

| Paper | Venue | Year | Links |
|-------|-------|------|-------|
| **Deep Reinforcement Learning of Volume-guided Progressive View Inpainting for 3D Point Scene Completion from a Single Depth Image** | CVPR (Oral) | 2019 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/1903.04019) |
| **Crafting a Toolchain for Image Restoration by Deep Reinforcement Learning** | CVPR (Spotlight) | 2018 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/1804.03312) |
| **Fully Convolutional Network with Multi-Step Reinforcement Learning for Image Processing** | AAAI | 2019 | [![Paper](https://img.shields.io/badge/Paper-red)](https://ojs.aaai.org/index.php/AAAI/article/view/4240) |
| **Path-Restore: Learning Network Path Selection for Image Restoration** | TPAMI | 2021 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/1904.10343) |
| **MOERL: When Mixture-of-Experts Meet Reinforcement Learning for Adverse Weather Image Restoration** | ICCV | 2025 | [![Paper](https://img.shields.io/badge/Paper-red)](https://openaccess.thecvf.com/content/ICCV2025/html/Wang_MOERL_When_Mixture-of-Experts_Meet_Reinforcement_Learning_for_Adverse_Weather_Image_ICCV_2025_paper.html) |
| **EditScore: Unlocking Online RL for Image Editing via High-Fidelity Reward Modeling** | ICLR | 2026 | [![Paper](https://img.shields.io/badge/Paper-red)](https://openreview.net/forum?id=E7YpL4L4Xh) |

---

### 6. 3D Vision & View Planning

> RL for next-best-view selection, 3D scene reconstruction, and point cloud understanding.

| Paper | Venue | Year | Links |
|-------|-------|------|-------|
| **A Reinforcement Learning Approach to the View Planning Problem** | CVPR | 2017 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/1610.06204) |
| **Learning to Look Around: Intelligently Exploring Unseen Environments for Unknown Tasks** | CVPR | 2018 | [![Paper](https://img.shields.io/badge/Paper-red)](https://openaccess.thecvf.com/content_cvpr_2018/papers/Jayaraman_Learning_to_Look_CVPR_2018_paper.pdf) |
| **Next-Best View Policy for 3D Reconstruction** | ECCV Workshop | 2020 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/2008.12664) |
| **Active 3D Shape Reconstruction from Vision and Touch** | NeurIPS | 2021 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/2107.09584) |
| **GenNBV: Generalizable Next-Best-View Policy for Active 3D Reconstruction** | CVPR | 2024 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/2402.16174) |

---

### 7. Medical Image Analysis

> RL for landmark detection, lesion localization, and anatomy-aware segmentation.

| Paper | Venue | Year | Links |
|-------|-------|------|-------|
| **Communicative Reinforcement Learning Agents for Landmark Detection in Brain Images** | MICCAI MLCN Workshop | 2020 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/2008.08055) |
| **Iteratively-Refined Interactive 3D Medical Image Segmentation with Multi-Agent Reinforcement Learning** ⭐ | CVPR | 2020 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/1911.10334) |
| **Automatic View Planning with Multi-scale Deep Reinforcement Learning Agents** | MICCAI | 2018 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/1806.03228) |
| **Sequential Attention-based Sampling for Histopathological Analysis** | NeurIPS | 2025 | [![Paper](https://img.shields.io/badge/Paper-red)](https://neurips.cc/virtual/2025/loc/san-diego/poster/115302) |
| **An Artificial Agent for Robust Image Registration** | AAAI | 2017 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/1611.10336) |
| **Active MR k-Space Sampling with Reinforcement Learning** | MICCAI | 2020 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/2007.10469) |


---

### 8. Visual Navigation & Embodied AI

> RL agents that learn to navigate and reason about 3D environments from visual observations.

| Paper | Venue | Year | Links |
|-------|-------|------|-------|
| **Target-driven Visual Navigation in Indoor Scenes using Deep Reinforcement Learning** ⭐ | ICRA | 2017 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/1609.05143) |
| **Cognitive Mapping and Planning for Visual Navigation** ⭐ | CVPR | 2017 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/1702.03920) |
| **Embodied Question Answering** ⭐ | CVPR | 2018 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/1711.11543) |
| **Neural Map: Structured Memory for Deep Reinforcement Learning** | ICLR | 2018 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/1702.08360) |
| **Learning to Navigate in Cities Without a Map** ⭐ | NeurIPS | 2018 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/1804.00168) |
| **Visual Semantic Navigation using Scene Priors** | ICLR | 2019 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/1810.06543) |
| **DD-PPO: Learning Near-Perfect PointGoal Navigators from 2.5 Billion Frames** ⭐ | ICLR | 2020 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/1911.00357) |
| **End-to-End Training of Deep Visuomotor Policies** ⭐ | JMLR | 2016 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/1504.00702) |
| **Vision-and-Language Navigation: Interpreting Visually-Grounded Navigation Instructions in Real Environments** ⭐ | CVPR | 2018 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/1711.07280) |
| **Habitat: A Platform for Embodied AI Research** 📊 | ICCV | 2019 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/1904.01201) |
| **Learning to Explore using Active Neural SLAM** | ICLR | 2020 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/2004.05155) |
| **REVERIE: Remote Embodied Visual Referring Expression in Real Indoor Environments** | CVPR | 2020 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/1904.10151) |
| **Object Goal Navigation using Goal-Oriented Semantic Exploration** | NeurIPS | 2020 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/2007.00643) |
| **SoundSpaces: Audio-Visual Navigation in 3D Environments** | ECCV | 2020 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/1912.11474) |
| **VLN-BERT: A Recurrent Vision-and-Language BERT for Navigation** | CVPR | 2021 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/2011.13922) |

---

### 9. Vision-Language Models with RL

> Aligning and improving multimodal large language models using reinforcement learning from human or AI feedback.

| Paper | Venue | Year | Links |
|-------|-------|------|-------|
| **LLaVA-RLHF: Aligning Large Multimodal Models with Factually Augmented RLHF** ⭐ | arXiv | 2023 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/2309.14525) |
| **RLHF-V: Towards Trustworthy MLLMs via Behavior Alignment from Fine-grained Correctional Human Feedback** ⭐ | CVPR | 2024 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/2312.00849) |
| **R1-V: Reinforcing Super-Human Visual Perception in Multimodal Large Language Models with Cold-Start RL** | arXiv | 2025 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/2503.06749) |
| **Visual-RFT: Visual Reinforcement Fine-Tuning** | arXiv | 2025 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/2503.01785) |
| **LLaVA-o1: Let Visual Language Models Reason Step-by-Step** | arXiv | 2024 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/2411.10440) |
| **DRESS: Instructing Large Vision-Language Models to Align and Interact with Humans via Natural Language Feedback** | CVPR | 2024 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/2311.10081) |
| **OmniAlign-V: Towards Enhanced Alignment of MLLMs with Comprehensive Human Feedback** | arXiv | 2025 | [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/abs/2502.18411) |


---

<div align="center">

**⭐ Star this repo if you find it useful!**  
Made with ❤️ for the CV + RL research community

</div>
